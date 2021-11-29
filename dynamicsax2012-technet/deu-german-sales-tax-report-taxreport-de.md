---
title: (DEU) German sales tax report (TaxReport_DE)
TOCTitle: (DEU) German sales tax report (TaxReport_DE)
ms:assetid: 77c9c499-4fec-4e51-9ef9-ce29e80c20bd
ms:mtpsurl: https://technet.microsoft.com/library/Hh496438(v=AX.60)
ms:contentKeyID: 37072020
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxReport_DE
---

# (DEU) German sales tax report (TaxReport\_DE) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **German sales tax report** displays and prints a summary of sales tax payments for legal entities operating in Germany, along with details of the sales tax payments. The details of this report are printed in the German layout with information that is based on how you set up the reporting codes in the **Sales tax reporting codes** form. This report is typically used by accounting managers to submit reporting information to sales tax authorities on a monthly basis.


> [!NOTE]
> <P>(DEU) This report is available only to legal entities whose primary address is in Germany.</P>



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
<td><p><strong>Create electronic tax document</strong></p></td>
<td><p>Select this check box to create an electronic document that contains the details of the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Documents submitted separately</strong></p></td>
<td><p>Select this check box if the printed report is not submitted along with the electronic document.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Style sheet for preview</strong></p></td>
<td><p>Enter the file name and path of the file in which the report is previewed. This file is used to preview the presentation of the report and is displayed in .xml format.</p></td>
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
<td><p>TaxReport_DE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReport_DE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReport_DE</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Sales tax payments</strong>. Click <strong>Print report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReportTmp\_DE table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReportDP_DE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Sales tax reporting codes (form)](https://technet.microsoft.com/library/aa588316\(v=ax.60\))

  


