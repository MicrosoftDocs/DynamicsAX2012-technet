---
title: Category consumption (actual vs. budget) report (ProjConsumCateg2Column)
TOCTitle: Category consumption (actual vs. budget) report (ProjConsumCateg2Column)
ms:assetid: 84feb5db-1cdc-41cc-b99f-bf2352b5fef3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa586969(v=AX.60)
ms:contentKeyID: 36941278
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjConsumCateg2Column
---

# Category consumption (actual vs. budget) report (ProjConsumCateg2Column) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze consumption for projects by category, and by comparing actual values and budgeted values.

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
<td><p>Select the project types that you want to include on the report. You must select at least one project type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include transaction types</strong></p></td>
<td><p>Select the transaction types that you want to include on the report. You must select at least one transaction type.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Project date</strong>)</p>
<p><strong>From date</strong> / <strong>Break date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for category earnings that are posted in projects.</p>
  
> [!NOTE]
> <P>When you select <STRONG>Sum</STRONG> in the <STRONG>Actual vs. budget</STRONG> field, the <STRONG>Break date</STRONG> value that you enter determines when the calculation of actual values ends and the calculation of budgeted values starts.</P>

</td>
</tr>
<tr class="even">
<td><p>(<strong>Ledger date</strong>)</p>
<p><strong>From date</strong> / <strong>Break date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for category earnings that are posted to the ledger.</p>
  
> [!NOTE]
> <P>When you select <STRONG>Sum</STRONG> in the <STRONG>Actual vs. budget</STRONG> field, the <STRONG>Break date</STRONG> value that you enter determines when the calculation of actual values ends and the calculation of budgeted values starts.</P>

</td>
</tr>
<tr class="odd">
<td><p><strong>Actual vs. budget</strong></p></td>
<td><ul>
<li><p>Select <strong>Deviation</strong> to display the difference between actual values and budgeted values.</p></li>
<li><p>Select <strong>Sum</strong> to display the actual values plus budgeted values.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Forecast model</strong></p></td>
<td><p>Select the forecast model that you want the report to use.</p>
  
> [!NOTE]
> <P>If you are using project budget control, select the budget forecast model that is used by this project.</P>

</td>
</tr>
<tr class="odd">
<td><p><strong>Skip zero</strong></p></td>
<td><p>Select whether to exclude rows where the amounts are equal to zero.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show amount</strong></p></td>
<td><p>Select how you want decimals to appear on the report, from the following options:</p>
<ul>
<li><p><strong>With decimals</strong> – Amounts are displayed to two decimal places of your company currency.</p></li>
<li><p><strong>Without decimals</strong> – Amounts are rounded to integers.</p></li>
<li><p><strong>Amount in 1,000</strong> – Amounts are rounded to the nearest 1,000 units of your company currency.</p></li>
<li><p><strong>Amount in 1,000,000</strong> – Amounts are rounded to the nearest million units of your company currency.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Show hour</strong></p></td>
<td><p>Select whether to display the quantity of hours, the cost value for hours posted to a category, or both on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Category consumption (actual vs. budget)</strong> form, select the project categories to include on the report. To add more than one category, click <strong>Add</strong>.</p></td>
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
<td><p>ProjConsumCateg2Column</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjConsumCateg2Column</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListProjConsumptionCategory2Column</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Project statements</strong> &gt; <strong>Consumption</strong> &gt; <strong>Consumption (actual vs. budget)</strong> &gt; <strong>Category consumption (actual vs. budget)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListProjConsumptionCateg2ColDP.processReport

  - ProjCategory table

  - PROJLISTPROJCONSUMPTIONTMP table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListProjConsumptionCateg2ColDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

