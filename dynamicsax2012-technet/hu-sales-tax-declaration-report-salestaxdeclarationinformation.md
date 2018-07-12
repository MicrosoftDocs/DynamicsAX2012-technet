---
title: (HU) Sales tax declaration report (SalesTaxDeclarationInformation)
TOCTitle: (HU) Sales tax declaration report (SalesTaxDeclarationInformation)
ms:assetid: db520be4-f8e3-40b6-b47b-b1c07cb0bc42
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ851131(v=AX.60)
ms:contentKeyID: 50173438
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HU) Sales tax declaration report (SalesTaxDeclarationInformation) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this report to create the monthly value-added tax (VAT) statement. This report includes the details about the sales taxes collected and owed for a given tax settlement period. To view the report, you must first create the report for the selected settlement period, and then you can print the report. This report is typically used by accountants, accounting managers, accounting supervisors, accounts payable centralized payment clerks, accounts payable clerks, accounts payable managers, accounts payable payment clerks, chief financial officers, and financial controllers.

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
<td><p><strong>Create report</strong></p></td>
<td><p>Open the <strong>Sales tax declaration information</strong> form, and generate the VAT statement for the selected settlement period. If you approve the statement, then no new transactions can be posted to the settlement period.</p></td>
</tr>
<tr class="even">
<td><p><strong>Clear period</strong></p></td>
<td><p>Clear a VAT statement that has already been generated, and then regenerate the statement.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cancel period</strong></p></td>
<td><p>Open a closed settlement period. This action clears the <strong>Approved</strong> check box, clears the <strong>Sales tax reporting</strong> field, and enables you to post additional transactions to the settlement period and then generate the VAT statement again.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print report</strong></p></td>
<td><p>Print the VAT statement report for the reporting period that you select in the bottom grid in the form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>Enter the date that you are generating the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Settlement period</strong></p></td>
<td><p>Select or view the code that represents the sales tax settlement period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>The start date of the settlement period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>The end date of the settlement period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax reporting</strong></p></td>
<td><p>The date that the sales tax statement is approved. This field is updated after you approve the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Approved</strong></p></td>
<td><p>A selected check box indicates that the sales tax statement has been approved. Sales tax transactions cannot be posted to the settlement period after the statement for the period has been approved.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Period start</strong></p></td>
<td><p>The start date of the settlement period for which the VAT statement report was generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>Period end</strong></p></td>
<td><p>The end date of the settlement period for which the VAT statement report was generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Reporting date</strong></p></td>
<td><p>The date that the VAT settlement report was generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>Use tax</strong></p></td>
<td><p>A selected check box indicates that use tax transactions are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Approve</strong></p></td>
<td><p>Select this check box to approve the sales tax statement. You can select this check box when you create the report, or you can select this check box after you review the report details.</p>
<p>To approve the report after the report has been generated, select the report in the lower grid in the form, click <strong>Print report</strong> to open the <strong>Sales tax declaration information</strong> form, and then select the <strong>Approve</strong> check box.</p>
<div>

> [!NOTE]
> <P>This field is displayed in the <STRONG>Sales tax declaration information</STRONG> form.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Include use-tax</strong></p></td>
<td><p>Select the check box to include use tax transactions on the settlement report.</p>
<div>

> [!NOTE]
> <P>This field is displayed in the <STRONG>Sales tax declaration information</STRONG> form.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Run mode</strong></p></td>
<td><p>Select which currency amounts to print on the report. Select from the following options:</p>
<ul>
<li><p><strong>Amounts in company currency for accounting</strong> – Print the values with the transaction exchange rate.</p></li>
<li><p><strong>Amounts in company currency for sales tax reporting</strong> – Print the values with the transaction sales tax exchange rate. This includes any lines that contain calculated sales tax discrepancies.</p></li>
<li><p><strong>Amounts in original currency</strong> – Print the values in the currency in which the transaction was posted.</p></li>
</ul>
<div>

> [!NOTE]
> <P>This field is displayed in the <STRONG>Sales tax declaration information</STRONG> form.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Printer</strong></p></td>
<td><p>The printer that is currently selected. To select a different printer, click <strong>Destinations ...</strong>.</p>
<p>This field is blank if <strong>Screen</strong> is selected in the <strong>Print destination</strong> field.</p>
<div>

> [!NOTE]
> <P>This field is displayed in the <STRONG>Sales tax declaration information</STRONG> form.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Print destination</strong></p></td>
<td><p>The destination where the report is produced. Click <strong>Destinations ...</strong> to change the destination for the report.</p>
<div>

> [!NOTE]
> <P>This field is displayed in the <STRONG>Sales tax declaration information</STRONG> form.</P>


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
<td><p>SalesTaxDeclarationInformation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SalesTaxDeclarationInformation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>This report does not have a menu item. Print the report directly from the <strong>Sales tax declaration information</strong> form. Use the navigation path in the next row to open the <strong>VAT reporting</strong> form, and then click <strong>Print report</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>VAT reporting</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpTaxReport\_HU


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the SalesTaxDeclarationInformationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

