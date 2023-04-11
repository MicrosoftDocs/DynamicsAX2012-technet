---
title: (SWE) Swedish sales tax report (TaxReport_SE)
TOCTitle: (SWE) Swedish sales tax report (TaxReport_SE)
ms:assetid: 58d09e27-2b00-41d2-9e5d-7994d52f265b
ms:mtpsurl: https://technet.microsoft.com/library/Hh352251(v=AX.60)
ms:contentKeyID: 36687877
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxReport_SE
---

# (SWE) Swedish sales tax report (TaxReport\_SE) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Swedish sales tax report** summarizes the sales tax component and is used to review the status of the sales tax process and sales tax transactions. This report is typically used by chief executive officers, compliance managers, accounting managers, collections managers, clerks, and accountants.


> [!NOTE]
> <P>(SWE) This report is available only to legal entities whose primary address is in Sweden.</P>



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
<td><p>TaxReport_SE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports/Reports/TaxReport_SE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReport_SE</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Sales tax payments</strong>. Click <strong>Print report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReportTmp\_SE table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReportDP_SE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


