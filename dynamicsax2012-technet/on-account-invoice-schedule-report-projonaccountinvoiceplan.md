---
title: On-account invoice schedule report (ProjOnAccountInvoicePlan)
TOCTitle: On-account invoice schedule report (ProjOnAccountInvoicePlan)
ms:assetid: 98fb1054-9eba-40f2-a9b8-a470f4ad38b7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa588131(v=AX.60)
ms:contentKeyID: 37820222
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjOnAccountInvoicePlan
---

# On-account invoice schedule report (ProjOnAccountInvoicePlan) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view information about on-account invoices for a project.

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
<td><p>Select the project types that you want to include on the report. You must select at least one type.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for project on-account transactions to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoiced</strong></p></td>
<td><p>Select whether to include hour transactions that have already been invoiced.</p></td>
</tr>
<tr class="even">
<td><p><strong>Chargeable</strong></p></td>
<td><p>Select whether to include chargeable hour transactions on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sorting</strong></p></td>
<td><p>Specify the first level of sorting on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer account</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>On-account invoice schedule</strong> form, in the <strong>Criteria</strong> field, select a customer account to include on the report. To add more than one customer account, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project contract ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>On-account invoice schedule</strong> form, in the <strong>Criteria</strong> field, select a project contract ID to include on the report. To add more than one project contract ID, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>On-account invoice schedule</strong> form, in the <strong>Criteria</strong> field, select a project ID to include on the report. To add more than one project ID, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales currency</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>On-account invoice schedule</strong> form, in the <strong>Criteria</strong> field, select a sales currency to include on the report. To add more than one sales currency, click <strong>Add</strong>.</p></td>
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
<td><p>ProjOnAccountInvoicePlan</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjOnAccountInvoicePlan</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjOnAccount</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Project invoices</strong> &gt; <strong>On-account invoice schedule</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjOnAccountInvoicePlanDP.processReport

  - ProjOnAccTrans table

  - ProjOnAccTransSale table

  - ProjTable

  - TmpProjOnAccountInvoicePlan table


> [!WARNING]
> <P>To determine where the data in the temp table comes from, view the cross-references for the ProjOnAccountInvoicePlanDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


