---
title: Budget control activity by project report (Public sector) (ProjAccountDetailHistory)
TOCTitle: Budget control activity by project report (Public sector) (ProjAccountDetailHistory)
ms:assetid: 7e8b844d-ad84-4565-9346-766a8c38576a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh334494(v=AX.60)
ms:contentKeyID: 36676481
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Public sector
- forecast model
- budget control
- budget cycle
- SSRS_Reports.Reports.ProjAccountDetailHistory
- budget balance
- Budget control account detail history report
---

# Budget control activity by project report (Public sector) (ProjAccountDetailHistory) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Budget control activity by project** report to view budget account entries for one or more projects from the **Project management and accounting** module. You can also select budget account entries by financial dimension and by a range of dates for projects and for entries in the general ledger.

Each report includes information arranged by project number and by account number. You can click links in a report to view project and account details in the **Projects** and **Chart of accounts** forms.

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
<td><p><strong>From date</strong> (<strong>Project dates</strong>)</p></td>
<td><p>Select a starting date for the project entries to include in the report.</p>
<div class="alert"> 

> [!NOTE]
> <P>You must select both <STRONG>Project dates</STRONG> and <STRONG>Ledger dates</STRONG> for this report.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong> (<strong>Project dates</strong>)</p></td>
<td><p>Select an ending date for project entries to include in the report.</p>
<div class="alert"> 

> [!NOTE]
> <P>You must select both <STRONG>Project dates</STRONG> and <STRONG>Ledger dates</STRONG> for this report.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong> (<strong>Ledger dates</strong>)</p></td>
<td><p>Select a starting date for entries to include from the general ledger.</p>
<div class="alert"> 

> [!NOTE]
> <P>You must select both <STRONG>Ledger dates</STRONG> and <STRONG>Project dates</STRONG> for this report.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong> (<strong>Ledger dates</strong>)</p></td>
<td><p>Select an ending date for entries to include from the general ledger.</p>
<div class="alert"> 

> [!NOTE]
> <P>You must select both <STRONG>Ledger dates</STRONG> and <STRONG>Project dates</STRONG> for this report.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Dimension focus</strong></p></td>
<td><p>Select a financial dimension set for the report. These were defined in the <strong>Financial dimension sets</strong> form. A financial dimension set is a named group of accounts or dimensions that contains either account values for the account or dimension values for a single dimension. Examples include main accounts, departments, and cost centers, or combinations such as a cost center and main account, or a department and cost center.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/aa597282(v=ax.60)">Financial dimension sets (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project ID</strong></p></td>
<td><p>Click <strong>Select</strong> to open an inquiry form to select one or more projects from the <strong>Project management and accounting</strong> module.</p>
<div class="alert"> 

> [!TIP]
> <P>You can leave this field blank to include all of the projects that match the other parameters that you selected.</P>
> <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa575929(v=ax.60)">Inquiry (form)</A>.</P>


</div></td>
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
<td><p>ProjAccountDetailHistory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjAccountDetailHistory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjAccountDetailHistory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Budgeting</strong> &gt; <strong>Reports</strong> &gt; <strong>Budget control</strong> &gt; <strong>Budget control activity by project</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjAccountDetailHistoryDP.processReport class instance method

  - ProjTable table

  - ProjTmpAccountDetailHistory table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Budget control account detail history report (Public sector) (BudgetAccountDetailHistory)](budget-control-account-detail-history-report-public-sector-budgetaccountdetailhistory.md)

  


