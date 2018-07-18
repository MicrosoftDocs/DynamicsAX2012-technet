---
title: Row structure where-used report (LedgerRowStructureWhereUsed)
TOCTitle: Row structure where-used report (LedgerRowStructureWhereUsed)
ms:assetid: 6ec8becc-dae9-4148-b522-bc588647bbdd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh801190(v=AX.60)
ms:contentKeyID: 43976709
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerRowStructureWhereUsed
---

# Row structure where-used report (LedgerRowStructureWhereUsed) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays the details of row definitions and financial statements that are used in the selected row definition.

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
<td><p>LedgerRowStructureWhereUsed</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerRowStructureWhereUsed</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerRowStructureWhereUsed</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Financial statement (traditional)</strong> &gt; <strong>Row definition</strong>. Click <strong>Where-used</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DIMENSIONHIERARCHY

  - LedgerBalHeaderDim

  - LedgerRowDef

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


