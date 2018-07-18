---
title: (AUT) Cross-border services report (LedgerXBorderActivityAT)
TOCTitle: (AUT) Cross-border services report (LedgerXBorderActivityAT)
ms:assetid: 2bb2b807-99fd-419a-af81-c06557164019
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335140(v=AX.60)
ms:contentKeyID: 36687350
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerXBorderActivityAT
- (AUT)
- Cross-border services report
---

# (AUT) Cross-border services report (LedgerXBorderActivityAT) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Cross-border services** report prints a summary of the incoming and outgoing cross-border services, countries that are the providers or recipients of the cross-border services, and net amounts paid for the services. This report is typically used by accounting managers, accountants, and sales managers to inquire into the status of sales transactions.


> [!NOTE]
> <P>(AUT) This report is available only to legal entities whose primary address is in Austria.</P>



## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>Select or enter the starting date of the reporting period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select or enter the ending date of the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Group by</strong></p></td>
<td><p>Select <strong>Service</strong> to sort the report details by the type of service. Select <strong>Country/region</strong> to sort the report details based on the country/region where the service was provided.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main account</strong></p></td>
<td><p>The main account number used to conduct the cross-border services.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>LedgerXBorderActivityAT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerXBorderActivityAT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerReport_XBorderActivityAT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Cross-border services</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerXBorderActivityTmpAT table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerXBorderActivityDPAT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


