---
title: (ITA) Domestic tax transactions (report)
TOCTitle: (ITA) Domestic tax transactions (report)
ms:assetid: 0a518c4d-f571-4b3b-984b-14e4341646b6
ms:mtpsurl: https://technet.microsoft.com/library/JJ874405(v=AX.60)
ms:contentKeyID: 50619722
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (ITA) Domestic tax transactions (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Click **General ledger** \> **Reports** \> **External** \> **Italian domestic tax transactions**.

Use this form to modify transaction information and to transfer transaction information that will be included on the Italian domestic transaction report. This report is filed electronically and is used to report transactions that include value-added tax (VAT).

You must report domestic tax transactions that contain a total tax base amount that exceeds specified thresholds for invoiced and not invoiced transactions.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Button</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Transfer</strong></p></td>
<td><p>Open the <strong>Transfer</strong> form to transfer the tax transactions to the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Validate</strong></p></td>
<td><p>Validate the information that you entered for the organization.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Export</strong></p></td>
<td><p>Open the <strong>Export</strong> form to export the report as an ACCII file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Copy report</strong></p></td>
<td><p>Create a copy of the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Apply threshold</strong></p></td>
<td><p>Apply the minimum threshold for including the transactions on the report. Any transactions that do not meet the threshold definition are not included in the report.</p>
<p>The threshold is specified in the <strong>Italian domestic tax report threshold</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tax transactions</strong></p></td>
<td><p>Open the <strong>Italian domestic tax transactions</strong> form to update the tax transaction to include on the report.</p></td>
</tr>
</tbody>
</table>


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
<td><p><strong>Year</strong></p></td>
<td><p>Enter the year for which the report is generated. For example, if the report is for the 2012 tax year, enter 2012.</p></td>
</tr>
<tr class="even">
<td><p><strong>Report type</strong></p></td>
<td><p>Select the type of report that you want to generate. The following options are available:</p>
<ul>
<li><p><strong>Original</strong> – Generate an original report.</p></li>
<li><p><strong>Replacement</strong> – Generate a report that contains corrections that were made to a report that was already submitted.</p></li>
<li><p><strong>Cancellation</strong> – Generate a report that cancels a previously created report. This report must include only the transaction lines that must be canceled.</p></li>
</ul>
<p>If you select <strong>Replacement</strong> or <strong>Cancellation</strong>, you must specify the report ID and document number of the report to be corrected or canceled. Enter these values in the <strong>Original report number</strong> field and the <strong>Original report document number</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p>The name of the organization.</p></td>
</tr>
<tr class="even">
<td><p><strong>City</strong></p></td>
<td><p>The city that the organization is located in.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Company county code</strong></p></td>
<td><p>The country/region code of the organization.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tax registration number</strong></p></td>
<td><p>The tax registration number that is assigned to the organization. The tax registration number is based on the location of the organization.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Fiscal code</strong></p></td>
<td><p>The fiscal code that is assigned to the organization.</p></td>
</tr>
<tr class="even">
<td><p><strong>Type of declarer</strong></p></td>
<td><p>Select the declarer type for the report from the following options:</p>
<ul>
<li><p><strong>Filing for same legal entity</strong> – The report is generated for the organization in which the tax transactions are transferred.</p></li>
<li><p><strong>Impact Analysis Objects</strong> – The report is generated and then filed through the Fiscal assistance center (CAF).</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>CAF fiscal code</strong></p></td>
<td><p>Enter the 11-digit CAF fiscal code.</p>
<p>This field is available only if you selected <strong>Impact Analysis Objects</strong> in the <strong>Type of declarer</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>CAF obligation</strong></p></td>
<td><p>Select the preparer of the report from the following options:</p>
<ul>
<li><p>&lt;blank&gt; – The CAF obligation does not apply to this report.</p></li>
<li><p><strong>Declaration prepared by legal entity</strong> – The report is prepared by the organization.</p></li>
<li><p><strong>Declaration prepared by declarer</strong> – The report is prepared by the declarer.</p>
<p>This option is available only if you selected <strong>Impact Analysis Objects</strong> in the <strong>Type of declarer</strong> field.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>CAF inscription number</strong></p></td>
<td><p>Enter the 5-digit CAF inscription number.</p></td>
</tr>
<tr class="even">
<td><p><strong>CAF transmission date</strong></p></td>
<td><p>Enter the transmission date for the selected declarer type.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Original report number</strong></p></td>
<td><p>Enter the report number that is assigned to the original report.</p>
<p>This field is available only if you selected <strong>Replacement</strong> or <strong>Cancellation</strong> in the <strong>Report type</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Original report document number</strong></p></td>
<td><p>Enter the document number that is assigned to the original document.</p>
<p>This field is available only if you selected <strong>Replacement</strong> or <strong>Cancellation</strong> in the <strong>Report type</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Multicompany communication</strong></p></td>
<td><p>Select this check box to indicate that transactions from multiple subsidiaries are included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Excluded</strong></p></td>
<td><p>Select this check box to exclude the tax transaction line from the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Direction</strong></p></td>
<td><p>Select whether the transaction line is for a sale or a purchase.</p></td>
</tr>
<tr class="even">
<td><p><strong>Account number</strong></p></td>
<td><p>Select the account number for the customer or vendor that is involved in the transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>Select the transaction date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Voucher</strong></p></td>
<td><p>Enter the voucher number.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Base amount</strong></p></td>
<td><p>Enter the transaction amount from which the sales tax amount is calculated.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tax amount</strong></p></td>
<td><p>The calculated sales tax amount.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment type</strong></p></td>
<td><p>Select the payment type for the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Credit note transaction</strong></p></td>
<td><p>Select this check box if this transaction line is for a credit note transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Contract</strong></p></td>
<td><p>Select the ID for the contract in which to group the transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Original invoice</strong></p></td>
<td><p>The identifier of the original invoice for the tax transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Original invoice date</strong></p></td>
<td><p>The date on which the original invoice was generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>Name</strong></p></td>
<td><p>The name of the customer or vendor for which the transaction invoice was generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Tax exempt number</strong></p></td>
<td><p>The tax exempt number that is assigned to the value-added tax (VAT)-registered customer or vendor.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fiscal code</strong></p></td>
<td><p>The fiscal code that is assigned to the customer or vendor that is not registered for VAT.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Record type</strong></p></td>
<td><p>The section in the report in which the transaction line is located.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice</strong></p></td>
<td><p>The invoice number of the transaction line.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Note</strong></p></td>
<td><p>Enter any additional notes about the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Italian domestic tax report contracts</strong></p></td>
<td><p>The contract identification number that is used to group the related transactions on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice</strong></p></td>
<td><p>The identification number of the invoice.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice date</strong></p></td>
<td><p>The date on which the invoice was posted.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Threshold base amount</strong></p></td>
<td><p>The amount of the transaction that the threshold is applied to.</p></td>
</tr>
<tr class="even">
<td><p><strong>Voucher</strong></p></td>
<td><p>The ledger voucher number for the transaction.</p></td>
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
<td><p>TaxReportDomesticTable_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>Forms\TaxReportDomesticTable_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReportDomesticTable_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Italian domestic tax transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CompanyInfo

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


