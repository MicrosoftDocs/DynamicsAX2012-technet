---
title: "What's new: Region-specific features for Eastern Europe (EEUR)"
TOCTitle: Region-specific features for Eastern Europe
ms:assetid: a9c8746f-192f-4b74-b7d3-ac8f936a9e66
ms:mtpsurl: https://technet.microsoft.com/library/Dn527196(v=AX.60)
ms:contentKeyID: 59623325
author: tonyafehr
ms.date: 11/20/2014
mtps_version: v=AX.60
---

# What's new: Region-specific features for Eastern Europe (EEUR) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we changed and added country/region-specific functionality for Eastern Europe. To learn more, refer to the tables that apply to your version of the product.

For more information about specific features for Eastern Europe, see [TechNet Library for Application Users – Eastern Europe](https://go.microsoft.com/fwlink/?linkid=299909).

## What’s new in cumulative update 8 for Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s New</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Call center</p></td>
<td><p>You can perform the following tasks for cash payments:</p>
<ul>
<li><p>Setup Payment method “Cash account” for Call center.</p></li>
<li><p>Post cash payments using Slip journal in the cash management module.</p></li>
</ul>
<p>You can perform the following tasks for prepayments:</p>
<ul>
<li><p>Create and post prepayments (include sales tax on prepayment) using special setup for Russia and Eastern Europe countries/regions.</p></li>
</ul>
<p>You can peform the following tasks for gift cards:</p>
<ul>
<li><p>Gift card issue with RU requirements for accounting</p></li>
<li><p>Gift card replenishment with RU requirements for accounting</p></li>
<li><p>Payment with gift cards</p></li>
<li><p>Refund to Gift card</p></li>
<li><p>Void operation for Gift card</p></li>
<li><p>Support Gift card policies</p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Customer invoice numbering in Lithuania and Latvia</p></td>
<td><p>In Lithuania and Latvia, you can assign specific numbers to sales invoices by user or user group.</p>
<p>For more information, see <a href="ltu-set-up-document-self-numbering-ranges.md">(LTU) Set up document self-numbering ranges</a>.</p></td>
</tr>
<tr class="even">
<td><p>Pre-acquisition handling of fixed assets</p></td>
<td><p>In Microsoft Dynamics AX 2012 R2, asset acquisition can be split into two separate steps, each of which has its own general ledger (GL) postings and fixed asset updates. Therefore, separate GL entries can be recorded when the asset is expensed, and when it is put into use. Depreciation is not permitted for assets that are still in the first step of the process (the Pre-acquisition stage). Pre-acquisition amounts can be viewed at the asset level.</p>
<p>For more information, see <a href="eeur-post-the-pre-acquisition-and-acquisition-of-a-fixed-asset.md">(EEUR) Post the pre-acquisition and acquisition of a fixed asset</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Print the tax directive on sales invoices</p></td>
<td><p>In Microsoft Dynamics AX 2012 R2, you can set up tax directives for the corresponding sales tax codes and print the tax directives on sales invoices in multiples languages for all Eastern European countries/regions.</p>
<p>For more information, see <a href="eeur-set-up-a-tax-directive.md">(EEUR) Set up a tax directive</a>.</p></td>
</tr>
<tr class="even">
<td><p>Round fixed asset depreciation amounts for Eastern European countries/regions</p></td>
<td><p>You can round fixed asset depreciation amounts up or down to the nearest number, as specified in the <strong>Round off depreciation</strong> field.</p>
<p>For more information, see <a href="eeur-about-rounding-off-depreciation-amounts.md">(EEUR) About rounding off depreciation amounts</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Tax reports can be based on the value-added tax (VAT) register date</p></td>
<td><p>In the Czech Republic and Poland, you can report tax information on a date that differs from the posting date. The <strong>Date of VAT register</strong> field is added to sales, purchase, and project documents. You can now generate various sales tax reports based on this date.</p>
<p>For more information, see <a href="eeur-activate-the-vat-registration-date-as-the-reporting-date-in-eu-sales-list-reports.md">(EEUR) Activate the VAT registration date as the reporting date in EU sales list reports</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create corrected invoices</p></td>
<td><p>For Eastern European countries/regions, you can create and post a canceling free text invoice without creating a corrective free text invoice.</p>
<p>For more information, see <a href="eeur-cancel-a-posted-free-text-invoice.md">(EEUR) Cancel a posted free text invoice</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Intrastat reporting for Eastern European countries/regions</p></td>
<td><p>You can generate Intrastat reports for Eastern European countries/regions in the generic .xml format. You can use Extensible Stylesheet Language for Transformations (XSLT) style sheets, and export country/region-specific Intrastat reports as .xml files or .csv files, based on the XSLT style sheets. You can use the XSLT style sheets to maintain multiple versions of the .xml or .csv files.</p>
<p>For more information, see <a href="ltu-export-an-intrastat-report-in-the-xml-format.md">(LTU) Export an Intrastat report in the XML format</a>.</p></td>
</tr>
<tr class="even">
<td><p>Customer and vendor settlement transactions can now be viewed for specific settlement types</p></td>
<td><p>A new helper table stores additional information about settlement transactions. You can view this information by clicking the <strong>Transactions on settlement</strong> button in the <strong>Customer transactions</strong> and <strong>Vendor transactions</strong> forms for the following settlement types:</p>
<ul>
<li><p>Exchange adjustments, when the settlement of an invoice and a payment generates a realized exchange rate difference</p></li>
<li><p>Posting profile changes, when two entries that have different posting profiles are settled</p></li>
<li><p>Prepayments that are converted to payments, when a prepayment is converted to a payment, or a payment is converted to a prepayment, by using the <strong>Prepayment handling</strong> form</p></li>
<li><p>Unrealized exchange rate adjustments, when the settlement of an invoice and a payment generates an unrealized exchange rate difference reversal</p></li>
<li><p>Cash discounts, when an invoice is settled with a payment that has a cash discount applied</p></li>
<li><p>Penny differences, when an invoice is settled with a payment for a slightly different amount (overpayment/underpayment)</p></li>
<li><p>Conditional tax postings, when an invoice is settled with a payment that has conditional tax applied</p></li>
<li><p>Cross-company settlements, when an invoice is settled with a payment between different companies by using intercompany functionality</p></li>
</ul>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj730993(v=ax.60)">(EEUR) Customer transactions (modified form)</a> and <a href="https://technet.microsoft.com/library/jj730985(v=ax.60)">(EEUR) Vendor transactions (modified form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>European Union (EU) sales list reporting for Eastern Europe</p></td>
<td><p>In Microsoft Dynamics AX 2012, support was added so that several EU member states could easily create a generic sales list report for the sale of goods and services to VAT-registered entities in other EU member states. In some cases, the sales list report could also be created for purchases. For Microsoft Dynamics AX 2012 R2, support is integrated for the following Eastern European countries/regions:</p>
<ul>
<li><p>Czech Republic</p></li>
<li><p>Hungary</p></li>
<li><p>Lithuania</p></li>
<li><p>Latvia</p></li>
<li><p>Poland</p></li>
<li><p>Estonia</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="cze-create-and-correct-records-in-the-eu-sales-list.md">(CZE) Create and correct records in the EU sales list</a></p></li>
<li><p><a href="hun-create-and-submit-the-eu-sales-list.md">(HUN) Create and submit the EU sales list</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/jj665133(v=ax.60)">(LTU) EU sales list (modified form)</a></p></li>
<li><p><a href="lva-print-the-eu-sales-list-report.md">(LVA) Print the EU sales list report</a></p></li>
<li><p><a href="pol-set-parameters-for-the-eu-sales-list.md">(POL) Set parameters for the EU sales list</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Make payments by using advance holders for Eastern European countries/regions</p></td>
<td><p>You can set up workers as advance holders and post vendor invoices with advance holder details. You can settle advance holder transactions to create general ledger entries. You can also enter advance holder transactions in general journals and slip journals.</p>
<p>For more information, see <a href="eeur-set-up-advance-holders.md">(EEUR) Set up advance holders</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Reason code support for projects</p></td>
<td><p>Fields for entering a reason code and reason comment have been added to the <strong>Invoice proposals</strong>, <strong>Invoice journals</strong>, and <strong>Select for credit note</strong>. This enhancement was made to support the Eastern European legislation requirement that original invoice references be printed on credit note documents.</p>
<p>This enhancement provides support for project invoices in the following Eastern European countries/regions:</p>
<ul>
<li><p>Czech Republic</p></li>
<li><p>Hungary</p></li>
<li><p>Latvia</p></li>
<li><p>Lithuania</p></li>
<li><p>Poland</p></li>
</ul>
<p>For more information, see <a href="eeur-configure-reason-code-requirements-for-credit-notes.md">(EEUR) Configure reason code requirements for credit notes</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fixed asset counting</strong> report</p></td>
<td><p>The <strong>Fixed asset counting</strong> report is available in Estonia and Latvia. For more information, see <a href="lva-generate-a-fixed-asset-counting-statement.md">(LVA) Generate a fixed asset counting statement</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Correction postings now use the storno accounting principle throughout Eastern Europe</p></td>
<td><p>Application of the storno accounting principle to correction postings is expanded to all Eastern European countries/regions. Storno postings are now available throughout Eastern Europe when you perform the following tasks:</p>
<ul>
<li><p>Post a sales order packing slip or purchase order product receipt.</p></li>
<li><p>Cancel a registered invoice in Accounts payable.</p></li>
<li><p>Post an inventory transaction or on-hand adjustment (receipt adjustment).</p></li>
<li><p>Post an inventory recalculation or closing (issue adjustment).</p></li>
<li><p>Cancel an inventory adjustment/recalculation.</p></li>
<li><p>Post a negative Hour, Expense, Item, or Fee journal.</p></li>
<li><p>Adjust a project transaction.</p></li>
</ul>
<p>For more information, see <a href="eeur-activate-storno-accounting.md">(EEUR) Activate storno accounting</a>.</p></td>
</tr>
<tr class="even">
<td><p>Exchange rate adjustments for bank account transactions and cash transactions for Eastern European countries/regions</p></td>
<td><p>If the exchange rate between the accounting currency and the reporting currency changes, you can revalue bank account transactions and cash transactions in the accounting currency. At the time of revaluation, you can generate reports to capture the following details:</p>
<ul>
<li><p>Exchange adjustments for a transaction</p></li>
<li><p>General ledger transactions in the reporting and accounting currencies, separately</p></li>
</ul>
<p>For more information, see <a href="eeur-calculate-exchange-rate-adjustments-for-bank-account-transactions.md">(EEUR) Calculate exchange rate adjustments for bank account transactions</a>.</p></td>
</tr>
</tbody>
</table>

  


