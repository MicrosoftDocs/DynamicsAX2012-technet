---
title: Row definition structure report (LedgerRowDefinitionPrint)
TOCTitle: Row definition structure report (LedgerRowDefinitionPrint)
ms:assetid: d8bbe672-33ce-4093-9c42-1f0d01dd7510
ms:mtpsurl: https://technet.microsoft.com/library/Hh781084(v=AX.60)
ms:contentKeyID: 43894490
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerRowDefinitionPrint
---

# Row definition structure report (LedgerRowDefinitionPrint) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays the ledger row definition structure.

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
<td><p><strong>Print</strong></p></td>
<td><p>Select whether to print the row definition as it is or in simulation mode.</p></td>
</tr>
<tr class="even">
<td><p><strong>Errors only</strong></p></td>
<td><p>Select this check box to print only errors.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print missing values</strong></p></td>
<td><p>Select this check box to print the missing values.</p></td>
</tr>
<tr class="even">
<td><p><strong>Updated</strong></p></td>
<td><p>Select this check box if a comparison to the updated version of the hierarchy is necessary.</p></td>
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
<td><p>LedgerRowDefinitionPrint</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\LedgerRowDefinitionPrint</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerRowDefinitionPrint</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Financial statement (traditional)</strong> &gt; <strong>Row definition</strong>. Click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerRowDefinitionPrintTmp table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the LedgerAccountSchedDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


