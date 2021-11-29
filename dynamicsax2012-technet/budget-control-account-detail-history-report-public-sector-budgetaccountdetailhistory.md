---
title: Budget control account detail history report (Public sector) (BudgetAccountDetailHistory)
TOCTitle: Budget control account detail history report (Public sector) (BudgetAccountDetailHistory)
ms:assetid: 554b5578-6add-4af2-bd95-5346278f63a6
ms:mtpsurl: https://technet.microsoft.com/library/Hh334480(v=AX.60)
ms:contentKeyID: 36676465
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BudgetAccountDetailHistory
---

# Budget control account detail history report (Public sector) (BudgetAccountDetailHistory) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Budget control account detail history** report to view budget account entries for the financial dimension that you select.

To create this report, select a financial dimension, budget model, and budget cycle time span from those that are used by your organization. Select dates that either match the selected budget cycle or select a range of dates in the fiscal calendar that is associated with the budget cycle. You can also select a range of specific accounts or all accounts that match the other parameters that you selected.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Field
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
  </tr>
  <tr>
    <td> <p> <strong>Dimension criteria:</strong> </p> </td>
    <td> <p>
   
	 Select a financial dimension set for the report. These were defined in the <strong>Financial dimension sets</strong> form. A financial dimension set is a named group of accounts or dimensions that contains either account values for the account or dimension values for a single dimension. Examples include main accounts, departments, and cost centers, or combinations such as a cost center and main account, or a department and cost center.
  </p> <p>
   
	 For more information, see <a href="https://technet.microsoft.com/library/aa597282(v=ax.60)" runat="server" xmlns="http://www.w3.org/1999/xhtml">Financial dimension sets (form)</a>.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Budget model</strong> </p> </td>
    <td> <p>
   
	 Select a budget model from those that are used by your organization. For more information, see <a href="create-budget-models.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Create budget models</a>.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Budget cycle time span</strong> </p> </td>
    <td> <p>
   
	 Select a budget cycle time span from those that are used by your organization. For more information, see <a href="https://technet.microsoft.com/library/hh227604(v=ax.60)" runat="server" xmlns="http://www.w3.org/1999/xhtml">Budget cycle time spans (form)</a>.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Include carry-forward amounts</strong> </p> </td>
    <td> <p>
   
	 Select this check box to include budget amounts carried forward from a previous fiscal year.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Dates to include</strong> </p> </td>
    <td> <p>
   
	 Select either <strong>Budget cycle</strong> or <strong>Date range</strong>. 
  </p> </td>
  </tr>
  <tr>
    <td rowspan="1"> <p> <strong>Budget cycle</strong> </p> </td>
    <td rowspan="1"> <p>
   
	 If you selected <strong>Budget cycle</strong>, select the name of a budget cycle. This will use the dates that were set up for the selected budget cycle in the <strong>Budget cycle time spans</strong> form. For more information, see <a href="https://technet.microsoft.com/library/hh227604(v=ax.60)" runat="server" xmlns="http://www.w3.org/1999/xhtml">Budget cycle time spans (form)</a>.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>From date</strong> </p> </td>
    <td> <p>
   
	 If you selected <strong>Date range</strong>, select the starting date for budget account entries to include in the report. This date must be in one or more of the fiscal years that are included in the fiscal calendar that was selected when the budget cycle time span was set up.
  </p> <p>
   
	 For example, a fiscal calendar for a budget cycle includes fiscal years with dates from January 1, 2010 to December 31, 2014. The <strong>From date</strong> cannot be before January 1, 2010.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>To date</strong> </p> </td>
    <td> <p>
   
	 If you selected <strong>Date range</strong>, select the ending date for budget account entries to include in the report. This date must be in one or more of the fiscal years that are included in the fiscal calendar that was selected when the budget cycle time span was set up.
  </p> <p>
   
	 For example, a fiscal calendar for a budget cycle includes fiscal years with dates from January 1, 2010 to December 31, 2014. The <strong>To date</strong> cannot be after December 31, 2014.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>From account</strong> </p> </td>
    <td> <p>
   
	 Select the first account in the range of accounts to include in the report.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>To account</strong> </p> </td>
    <td> <p>
   
	 Select the last account in the range of accounts to include in the report.
  </p> </td>
  </tr>
  <tr>
    <td rowspan="2"> <p> <strong>Select</strong> </p> </td>
    <td rowspan="1"> <p>
   
	 Click <strong>Select</strong> to open an inquiry form to select specific values for a dimension.
  </p> <p>
   
	 For example, for a Department dimension, select the Sales or Human Resources departments. For a Fund dimension, select one or more specific funds. For more information, see <a href="https://technet.microsoft.com/library/aa575929(v=ax.60)" runat="server" xmlns="http://www.w3.org/1999/xhtml">Inquiry (form)</a>.
  </p> </td>
  </tr>
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
<td><p>BudgetAccountDetailHistory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BudgetAccountDetailHistory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BudgetAccountDetailHistory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Budgeting</strong> &gt; <strong>Reports</strong> &gt; <strong>Budget control</strong> &gt; <strong>Budget control account detail history</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BudgetAccountDetailHistoryDP.processReport class instance method

  - BudgetAccountDetailTmpHistory table

  - BudgetSourceTracking table

  - BudgetSourceTrackingDetail table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Budget control activity by project report (Public sector) (ProjAccountDetailHistory)](budget-control-activity-by-project-report-public-sector-projaccountdetailhistory.md)

  


