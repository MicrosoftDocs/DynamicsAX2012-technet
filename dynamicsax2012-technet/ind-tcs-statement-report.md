---
title: (IND) TCS statement (report)
TOCTitle: (IND) TCS statement (report)
ms:assetid: 5aa4801c-09fd-41a4-91fb-ee1b65571f35
ms:mtpsurl: https://technet.microsoft.com/library/JJ969578(v=AX.60)
ms:contentKeyID: 51554464
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) TCS statement (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a quarterly statement by using Form 27EQ for Tax collected at source (TCS).

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
<td><p><strong>Statement filed earlier</strong></p></td>
<td><p>Select this check box if a TCS statement has previously been filed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Token number</strong></p></td>
<td><p>Select the token number assigned to the previously filed TCS statement.</p>
<p>This field is available only if you selected the <strong>Statement filed earlier</strong> check box.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Tax Account Number (TAN)</strong></p></td>
<td><p>Select the Tax Account Number (TAN) to identify TCS tax settlement periods.</p></td>
</tr>
<tr class="even">
<td><p><strong>Statement</strong></p></td>
<td><p>The type of statement to generate.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>Select the end date of the statement period.</p></td>
</tr>
<tr class="even">
<td><p><strong>Period end</strong></p></td>
<td><p>The quarter for which the statement is generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Responsible person</strong></p></td>
<td><p>Select the employee who is responsible for generating the TCS statement.</p></td>
</tr>
<tr class="even">
<td><p><strong>Designation</strong></p></td>
<td><p>Enter the designation of the person responsible for deducting the Tax deducted at source (TDS). Based on how your organization has determined the designation, you might, for example, enter <strong>Finance Manager</strong>, <strong>Compliance Manager</strong>, or <strong>Tax Accountant</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Printing date</strong></p></td>
<td><p>Select the date for printing the statement.</p></td>
</tr>
<tr class="even">
<td><p><strong>Name of the return preparation utility</strong></p></td>
<td><p>Specify the name of the utility that is used to prepare the tax return statement, based on the version of Microsoft Dynamics AX that you are using.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Generate e-file</strong></p></td>
<td><p>Select this check box to generate an e-file for the quarter.</p></td>
</tr>
<tr class="even">
<td><p><strong>Generate corrected e-file</strong></p></td>
<td><p>Select this check box to generate a corrected e-file for the quarter.</p></td>
</tr>
<tr class="odd">
<td><p><strong>File name</strong></p></td>
<td><p>Select the name and path of the file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Filed</strong></p></td>
<td><p>Select this check box to indicate that the statement has been filed.</p></td>
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
<td><p>TaxWithholdStatement</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxWithholdStatement</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxWithholdingStatementTDS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p><strong>Navigation Path Not Found</strong></p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxWithholdStatementTmpTrans

  - TaxWithholdSTatementTmpParticularInfo

  - TaxWithholdStatementTmpTransSummary

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


