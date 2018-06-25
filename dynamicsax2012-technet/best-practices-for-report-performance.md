---
title: Best Practices for Report Performance
TOCTitle: Best Practices for Report Performance
ms:assetid: dcd4d2ff-a477-4508-9bc3-2817450128a8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn251070(v=AX.60)
ms:contentKeyID: 54811747
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Best Practices for Report Performance [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This section contains guidance and best practices for ensuring good report performance.

## Use Set-based Operators Pattern to Improve Report Performance

Performing operations on multiple records at a time can dramatically reduce the number of SQL calls that are run for your report. The result is a dramatic increase in the performance and throughput of your report. Here is an introduction to the record set-based operators:

  - **insert\_recordset** allows you to copy multiple records from one or more tables directly into another table on a single database trip.

  - **update\_recordset** allows you to update multiple rows in a table on a single database trip to the server.

### ![Dn251070.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn251070.collapse_all(en-us,AX.60).gif")When to use this pattern

Use the set-based operators pattern to create Microsoft Dynamics AX reports in the following situations:

  - Multiple records’ amounts are summarized into one amount.

  - The individual transactions are not displayed on the report.

  - The logic to retrieve the summarized amounts is relatively simple.

### ![Dn251070.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn251070.collapse_all(en-us,AX.60).gif")When not to use this pattern

Don’t use this pattern if:

  - Each individual transaction is displayed on the report.

  - Complex code is needed to summarize the amounts.

### ![Dn251070.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn251070.collapse_all(en-us,AX.60).gif")Description of the pattern

This pattern involves using temp tables and defining business logic for them.

#### ![Dn251070.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn251070.collapse_all(en-us,AX.60).gif")Temp Tables

There are three temp tables involved:

1.  **A Values table.** This table contains a set of records that holds the balances for a single value (column in the report). This table has a TableType of TempDB. This table generally has just two fields: an identity field and an amount field.

2.  **A Processing table.** This is an intermediate table that allows balances to be updated as they become known. This table has a TableType of TempDB. This table will generally have three types of fields:
    
    1.  Key\\identity fields
    
    2.  Amount fields
    
    3.  Type fields (optional)

3.  **The temp table returned from the RDP class.** This is the table that holds the data that the SSRS report will use. This table will generally be similar in structure to the Processing table however there may be some differences depending on the requirements of the SSRS report. This table has a TableType of InMemory.

#### ![Dn251070.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn251070.collapse_all(en-us,AX.60).gif")Business Logic

The first part of the process is to populate the Processing table with a record for each of the primary entities involved. For instance, a record for each Main Account, Customer, or Vendor for which the report is being generated. Because every report has a backing query, that query must be run to get the data that is relevant for report. The necessary records can be inserted into the Processing table with either a RecordInsertList or insert\_recordset statement. At this point the Processing table will be populated with one record per entity and only the key\\identity fields are populated.

For example, we may start with a table that looks like this:

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>AccountNum</p></th>
<th><p>AccountName</p></th>
<th><p>OpeningBalance</p></th>
<th><p>ClosingBalance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>2031</p></td>
<td><p>Stone University</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>2002</p></td>
<td><p>River Hotel</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>1202</p></td>
<td><p>Owl Wholesale</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


The next step is to get the summarized amounts per entity. The first stage for this is to insert records with the summarized amounts into the Values table. An insert\_recordset statement is written that will group by the identity of the entity involved and will perform an aggregate function to get the summarized amount. Here is an example:

    insert_recordset _tmpValue
    (CustomerNum, Balance)
    select CustomerNum
    from tmpProcessing
    group by tmpProcessing.CustomerNum
    join sum(AccountingCurrencyAmount) from generalJournalAccountEntry
    The next stage is to have an update_recordset statement to ‘transfer’ the summarized amounts from the Values table buffer to the Processing table.
    update_recordset tmpProcessing setting Balance = tmpValue.Balance
    join tmpValue
    where
    tmpValue.CustomerNum == tmpProcessing.CustomerNum

At this point the Processing table now looks like this:

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>AccountNum</p></th>
<th><p>AccountName</p></th>
<th><p>OpeningBalance</p></th>
<th><p>ClosingBalance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>2031</p></td>
<td><p>Stone University</p></td>
<td><p>15689.15</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>2002</p></td>
<td><p>River Hotel</p></td>
<td><p>8199899.75</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>1202</p></td>
<td><p>Owl Wholesale</p></td>
<td><p>31358.88</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


This process is repeated for each summarized amount that is required by the report. Once the Processing table is fully populated it is then translated into records that will be returned by the RDP class. This translation process can handle any miscellaneous business logic that is required by the report.


> [!NOTE]
> <P>Decreasing the number of trips to the SQL server can dramatically improve the performance of your report. However, there are some limitations to be aware of with this pattern. If complex business logic is required to generate the summarized amounts then it can be difficult or impossible to write a set-based operation with all the joins and conditions that would be required to properly calculate the summarized amount.</P>



#### ![Dn251070.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn251070.collapse_all(en-us,AX.60).gif")Examples of this pattern

For an example of this pattern see the LedgerTurnoverAndBalanceDP class. The associated temp tables are: LedgerTurnoverAndBalanceTmp, LedgerTurnoverTmpBalanceValue, and LedgerTurnoverAndBalanceTempProcessing.

## See also

insert\_recordset

update\_recordset

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

