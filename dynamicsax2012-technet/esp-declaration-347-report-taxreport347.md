---
title: (ESP) Declaration 347 report (TaxReport347)
TOCTitle: (ESP) Declaration 347 report (TaxReport347)
ms:assetid: 4e3851c5-6912-48cd-83f7-bc56e4848541
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335146(v=AX.60)
ms:contentKeyID: 36687357
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- declaration 347
- "347"
- SSRS_Reports.Reports.TaxReport347Report
---

# (ESP) Declaration 347 report (TaxReport347) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Declaration 347** report prints the details of all sales and purchase transactions that exceed EUR 3,000 for customers and vendors with an address in Spain.


> [!NOTE]
> <P>(ESP) This report is available only to legal entities whose primary address is in Spain.</P>



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
<td><p><strong>Fiscal year</strong></p></td>
<td><p>The fiscal year for which the <strong>Declaration 347</strong> report is generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>Declaration 347</strong></p></td>
<td><p>The record ID of the tax report 347 declaration.</p></td>
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
<td><p>TaxReport347</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReport347</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReport347</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Report 347</strong> &gt; <strong>Declaration 347</strong>. Click <strong>Output</strong> &gt; <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReport347ReportTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReport347DP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


