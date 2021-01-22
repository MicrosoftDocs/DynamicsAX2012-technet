---
title: Committed costs - items report (ProjListTransCommittedCost)
TOCTitle: Committed costs - items report (ProjListTransCommittedCost)
ms:assetid: 7a555d9d-253e-4efb-9853-d325748e1111
ms:mtpsurl: https://technet.microsoft.com/library/Aa586717(v=AX.60)
ms:contentKeyID: 37832013
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListTransCommittedCost
---

# Committed costs - items report (ProjListTransCommittedCost) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view a list of products that your company has committed to purchase for projects.

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
<td><p><strong>Include project types</strong></p></td>
<td><p>Select the types of projects that you want to include on the report. You must select at least one project type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include booking types</strong></p></td>
<td><p>Select the document types for the commitments that you want to include on the report. You must select at least one document type.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Committed date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Select the project date range for commitments that you want the report to include.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show</strong></p></td>
<td><p>Select whether to include all or only open orders on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Layout - rows</strong></p>
<p><strong>Level 1</strong> / <strong>Level 2</strong> / <strong>Level 3</strong></p></td>
<td><p>Select how you want to group the information on the report. Transactions are listed by <strong>Level 1</strong>, then by <strong>Level 2</strong>, and then by <strong>Level 3</strong>. For each level, you can select <strong>Project</strong>, <strong>Category</strong>, <strong>Worker/item</strong>, <strong>Order</strong> or <strong>Vendor</strong>.</p>
<div class="alert">

> [!NOTE]
> <P>You must select a value for <STRONG>Level 1</STRONG>.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Show amount</strong></p></td>
<td><p>Select how you want decimals to appear on the report from the following options:</p>
<ul>
<li><p><strong>With decimals</strong> – Amounts are displayed to two decimals of your company currency.</p></li>
<li><p><strong>Without decimals</strong> – Amounts are rounded to integers.</p></li>
<li><p><strong>Amount in 1,000</strong> – Amounts are rounded to the nearest 1,000 units of your company currency.</p></li>
<li><p><strong>Amount in 1,000,000</strong> – Amounts are rounded to the nearest million units of your company currency.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Specify transactions</strong></p></td>
<td><p>Select whether to display all transactions in a project by project date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Committed costs - items</strong> form, in the <strong>Criteria</strong> field, select a project to include on the report. To add more than one project, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Committed costs - items</strong> form, in the <strong>Criteria</strong> field, select a project category to include on the report. To add more than one project category, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Worker</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Committed costs - items</strong> form, in the <strong>Criteria</strong> field, select a worker to include on the report. To add more than one worker, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Committed costs - items</strong> form, in the <strong>Criteria</strong> field, select an item to include on the report. To add more than one item, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Dimension</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Committed costs - items</strong> form, in the <strong>Criteria</strong> field, select a dimension to include on the report. To add more than one dimension, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor account</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Committed costs - items</strong> form, in the <strong>Criteria</strong> field, select a vendor account to include on the report. To add more than one vendor account, click <strong>Add</strong>.</p></td>
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
<td><p>ProjListTransCommittedCost</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListTransCommittedCost</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListProjCommittedCost</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Committed costs</strong> &gt; <strong>Committed costs</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListTransCommittedCostDP.processReport

  - ProjListTransCommittedCostTmp table

  - CostControlTransCommittedCost table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListTransCommittedCostDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


