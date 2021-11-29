---
title: Project transactions report (ProjListTransProject)
TOCTitle: Project transactions report (ProjListTransProject)
ms:assetid: 29ce6d26-00ef-4372-830f-a0b4d293d252
ms:mtpsurl: https://technet.microsoft.com/library/Aa500650(v=AX.60)
ms:contentKeyID: 37831985
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Project transactions report (ProjListTransProject) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view details of transactions that are posted to projects as of a specified date.

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
<td><p><strong>Invoice</strong></p></td>
<td><p>Select whether to include transactions on the report from the following options:</p>
<ul>
<li><p><strong>Nonchargeable</strong> – Include transactions for which you do not invoice a customer.</p></li>
<li><p><strong>Chargeable</strong> – Include transactions for which you send customer invoices.</p></li>
<li><p><strong>Invoiced</strong> – Include transactions that you have already invoiced to customers.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Project ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transactions - project</strong> form, select a project ID to include on the report. To add more than one project, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Hours</strong> - <strong>Project date</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transactions - project</strong> form, select a starting date for hour transactions in projects to include on the report. To add more than one starting date for hour transactions, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Expense</strong> - <strong>Project date</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transactions - project</strong> form, select a starting date for expense transactions in projects to include on the report. To add more than one starting date for expense transactions, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Fee</strong> - <strong>Project date</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transactions - project</strong> form, select a starting date for fee transactions in projects to include on the report. To add more than one starting date for fee transactions, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Items</strong> - <strong>Project date</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transactions - project</strong> form, select a starting date for item transactions in projects to include on the report. To add more than one starting date for item transactions, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>On-account</strong> - <strong>Project date</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transactions - project</strong> form, select a starting date for on-account transactions in projects to include on the report. To add more than one starting date for on-account transactions, click <strong>Add</strong>.</p></td>
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
<td><p>ProjListTransProj</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListTransProj</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListTransProject</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Project transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListTransProjDP.processReport

  - ProjCostTrans table

  - ProjCostTransSale table

  - ProjEmplTrans table

  - ProjEmplTransSale table

  - ProjItemTrans table

  - ProjItemTransSale table

  - ProjOnAccTrans table

  - ProjOnAccTransSale table

  - ProjRevenueTrans table

  - ProjRevenueTransSale table

  - ProjTable

  - TmpProjTransList table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListTransProjDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


