---
title: Picking list report (ProdPicklist)
TOCTitle: Picking list report (ProdPicklist)
ms:assetid: a5f59e15-6293-4194-86e3-d44468f57bc1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa617995(v=AX.60)
ms:contentKeyID: 36060136
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProdPicklist
---

# Picking list report (ProdPicklist) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Picking list** report to print a list of the materials to pick per production order.

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
<td><p>Print transactions</p></td>
<td><p>Select this check box to include transactions that are posted to time and material projects.</p></td>
</tr>
<tr class="even">
<td><p>Use delivery note layout</p></td>
<td><p>Print information about the connected vendor purchase and transfer orders.</p></td>
</tr>
<tr class="odd">
<td><p>Use quantity</p></td>
<td><p>Select the consumption quantity that you want the report to use. The options are as follows:</p>
<p><strong>Proposal</strong>—The estimated item consumption.</p>
<p><strong>Consumption</strong>—The reported consumption.</p>
<div class="alert">

> [!NOTE]
> <P>This field is relevant when you select the <STRONG>Use delivery note layout</STRONG> field.</P>


</div></td>
</tr>
<tr class="even">
<td><p>View</p></td>
<td><p>Use the check boxes in this field group to specify the inventory dimensions that you want to include in the report. The options are as follows:</p>
<p><strong>Configuration</strong></p>
<p><strong>Size</strong></p>
<p><strong>Color</strong></p>
<p><strong>Site</strong></p>
<p><strong>Warehouse</strong></p>
<p><strong>Batch number</strong></p>
<p><strong>Location</strong></p>
<p><strong>Pallet ID</strong></p>
<p><strong>Serial number</strong></p></td>
</tr>
<tr class="odd">
<td><p>Picking list journal</p></td>
<td><p>Click <strong>Select</strong> and then create a query for a specific picking list journal.</p></td>
</tr>
<tr class="even">
<td><p>Production</p></td>
<td><p>Click <strong>Select</strong> and then create a query for a specific production order.</p></td>
</tr>
<tr class="odd">
<td><p>Voucher</p></td>
<td><p>Click <strong>Select</strong> and then create a query for the voucher number in the ledger.</p></td>
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
<td><p>ProdPicklist</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProdPicklist</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProdPicklist</p>
<p>ProdPicklistShowDialog</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Production control</strong> &gt; <strong>Reports</strong> &gt; <strong>Production papers</strong> &gt; <strong>Picking list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProdPickListTmp table


> [!NOTE]
> <P>To learn where the data in the temp tables comes from, view the cross-references for the ProdPicklistDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

