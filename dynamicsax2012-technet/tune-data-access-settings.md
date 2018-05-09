---
title: Tune data access settings
TOCTitle: Tune data access settings
ms:assetid: f799430e-56b0-4b77-abdc-517820390dd2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569634(v=AX.60)
ms:contentKeyID: 36584409
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- database performance
- server configuration utility
- Tune database settings
- tune queries
---

# Tune data access settings 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You might want to tune the database settings for Microsoft Dynamics AX to improve performance. Settings that you can tune include connections, query settings for the use of literals, string functions, or hints, concurrency mode used for database changes, and the table and index options, such as table and index data compression, and index fill factor and sort in tempdb settings.

Before changing settings, you should trace the usage of your Microsoft Dynamics AX database to ensure that you have clear understanding of performance under the current settings.

Test all tuning changes before implementing them in a production environment. In a test or development environment, make a single change and then test your system's performance before making another change.

## Tune connections

The following table lists common connection issues, and also some adjustments to try in the **Server Configuration Utility**.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Symptom</p></th>
<th><p>Adjustments to try</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Queries that return a large number of rows execute slowly.</p></td>
<td><p>Increase the <strong>Maximum buffer size</strong> value in small increments.</p>
<p>If this adjustment has worked, the number of round trips to the database, as measured in Performance Monitor by a decrease in the value of <strong>SQL Server statistics: batchrequestsPerSecond</strong> value. Stop increasing the value when the rate of improvement diminishes.</p>
<p>You may also want to change the <strong>Maximum buffer size</strong> value if you receive an error similar to the following:</p>
<p><strong>The total, internal size of the records in your joined Select statement is 29374 bytes, but Microsoft Dynamics is by default performance-tuned not to exceed 27646 bytes. It is strongly recommended that you split your tables(s) into smaller units.</strong></p>
<p>Maximum buffer size refers to the size of buffer the kernel allocates for holding input/output data to and from SQL Server. The buffer can be used to hold more than one row of the entire result set for output binding, and it should be allocated large enough to hold at least one row. The buffer size needed for one row depends on the number of tables joined (exist join excluded) and the size of the aggregated table columns. When large numbers of joins are used, or wide tables, a customer may encounter the issue that the maximum buffer size is less than the space needed to hold one row of the result set.</p>
<p>Due to the way the kernel handles data binding, the aggregated table column size is always the width of the entire table. Therefore, attempting to resolve the issue by limiting the field projection list does not help. You can fix the issue by rewriting the join, or by increasing the <strong>Maximum buffer size</strong> value.</p>
<p>Because large joins and wide rows may lead to performance issues, we use this limit to catch performance issues and ask customers to rethink their joins.</p></td>
</tr>
<tr class="even">
<td><p>Results for ad hoc queries are returned slowly.</p></td>
<td><p>Verify that the appropriate indexes are in place.</p></td>
</tr>
</tbody>
</table>


## Tune queries

If queries in the system are running slowly, you may want to change settings for literals, string functions, or hints.

## Adjust the use of hints

In Microsoft Dynamics AX, you can allow developers to override the index selected by the query optimizer. In most situations, allowing the query optimizer to select an index for a query results in improved performance.

## Changes in the use of hints

The following changes to hints have been made:

  - The OPTION (FIRSTFAST) hint is applied by default for form data sources. It can be suppressed, or set to a specific value. Use of this option appends an OPTION (FAST) to the SQL Server query.

  - OPTION( FAST) is now set to what we expect the number of rows to be returned to the database in a single roundtrip. This is based on maximum buffer size.

  - FASTFORWARD cursors are used for all user queries unless the query is a full text search.

## Change table and index options

Table and index options that can be changed from within Microsoft Dynamics AX include table compression settings, and index compression, fill factor, and sort in tempdb settings.

## Data compression options

If you have appropriate hardware, we recommend that you set all tables and indexes to use page-level compression. Compression saves disk space and memory consumption, but increases CPU consumption. When page-level compression has been set, expect between 10-15 percent additional CPU consumption.

If you are concerned about CPU consumption, we recommend that you start by setting the ten largest tables in your system to use table compression.

Use the guidance in the following resources to help you determine how or whether to compress your tables and indexes:

  - SQL Server Books online: [Creating Compressed Tables and Indexes](http://go.microsoft.com/fwlink/?linkid=210430)

  - SQLCat article: [Data Compression: Strategy, Capacity Planning and Best Practices](http://go.microsoft.com/fwlink/?linkid=210431)

  - Database Engine team blog post: [Compression Strategies](http://go.microsoft.com/fwlink/?linkid=210424).  

## Fill factor options

We recommend that you not set the fill factor options (fill factor and pad index) for all indexes. Only set fill factor values on indexes that show rapid fragmentation, where fragmentation has a performance penalty. Adjusting fill factor can be important for tables that you want to retrieve sequential rows from, for example, sales line.

We recommend that you work with your database administrators to identify the tables to set this value for.

## Sort in tempdb

We recommend that you not set the sort in tembdp options for all indexes. Only enable sort in tempdb for indexes that show rapid fragmentation, where fragmentation has a performance penalty.

We recommend that you work with your database administrators to identify the tables to set this value for.

## To change table and index options

1.  Click **System administration** \> **Periodic** \> **Database** \> **SQL administration**. Select all tables, all indexes, or a specific table or index, and then click **Table and index options**.

2.  Select the options to set, and then click **Save**.
    
    The SQL statement that will be executed is displayed at the bottom of the form.
    

    > [!IMPORTANT]
    > <P>The changes that you have made will not be applied unless you specify that they should be applied by using the <STRONG>SQL administration</STRONG> form.</P>
    > <P>To turn off data compression, click <STRONG>Enable compression</STRONG>, click <STRONG>None</STRONG> for the type of compression, and then close the <STRONG>Select table and index options</STRONG> form, and then click <STRONG>Apply compression</STRONG> in the <STRONG>SQL administration</STRONG> form.</P>



3.  To apply changes in the **SQL administration** form:
    
      - For tables, click **Table actions**, and then click **Apply compression**.
    
      - For indexes, click **Index actions**, and then click **Reindex**.

## Change the concurrency mode

Concurrency mode settings enable you to reduce locking conflicts in your system. Set concurrency mode settings only at the table or statement level, not throughout your Microsoft Dynamics AX program.

## Optimistic concurrency

An optimistic concurrency strategy does not lock data when the data is retrieved from the database for future modification. Therefore, no locks are held while filters and other business logic are being applied. Data is locked only when an update is performed. If any data has been changed by another transaction between the time of the retrieval and the time of the update, the change is detected and an Infolog exception is displayed.

## Pessimistic concurrency

A pessimistic concurrency strategy uses an update lock to lock data when the data is retrieved from the database for future modification. Locks are held while filters and other business logic are being applied, in addition to being held during an update. Data cannot be changed by other transactions.

Acquiring an update lock for a large volume of rows increases the lock escalation from row level to table level in SQL Server. This can block other users and reduce transaction throughput.

## Table-level concurrency settings

If the global concurrency mode is set to **Optimistic concurrency mode enabled per table**, table-level control of concurrency settings is available using the **OccEnabled** property.

## Runtime update options

If you are encountering many update errors, you may want to use the runtime update options to help troubleshoot. These options are intended for temporary use only, as they might significantly slow performance.

Use **Writes all UPDATE conflict exceptions to the log** to write all update conflict exceptions to the log.

Use **Update record version automatically** to have Microsoft Dynamics AX search in memory for the recordID every time that that a record is updated, and then change the update values in all instances of the record.

If you have a table set to optimistic concurrency, and you are experiencing optimistic concurrency violations that affect the performance of the transactions that use the table, then first set the **Writes all UPDATE conflict exceptions to the log** option. If, from your analysis, it appears that the use of optimistic concurrency is causing a problem, then set the table to pessimistic concurrency.

## To change concurrency settings

1.  Click **System administration** \> **Setup** \> **Database** \> **Select concurrency mode**.

2.  Select the appropriate concurrency mode and runtime options for your environment.

3.  Click **Close**.

## Statement-level concurrency settings

You can use the optimisticlock or pessimisticlock keywords in a SELECT statement to override the global or table concurrency mode settings.

For more information, see the following topics:

  - [Best Practice Performance Optimizations: Database Design and Operations](https://technet.microsoft.com/en-us/library/aa854605\(v=ax.60\))

  - [Transaction Integrity](https://technet.microsoft.com/en-us/library/aa622564\(v=ax.60\))

  - [Exception Handling with try and catch Keywords](https://technet.microsoft.com/en-us/library/aa893385\(v=ax.60\))

  - [Select Statement Syntax](https://technet.microsoft.com/en-us/library/aa656402\(v=ax.60\))

  - [Table Properties](https://technet.microsoft.com/en-us/library/aa871620\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

