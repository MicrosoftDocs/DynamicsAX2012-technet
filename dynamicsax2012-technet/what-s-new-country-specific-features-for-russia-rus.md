---
title: "What's new: Country-specific features for Russia (RUS)"
TOCTitle: Country-specific features for Russia
ms:assetid: 8c154677-693f-4c6c-b737-91d7ef371da5
ms:mtpsurl: https://technet.microsoft.com/library/Dn527162(v=AX.60)
ms:contentKeyID: 59623292
author: Khairunj
ms.date: 06/09/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for Russia (RUS) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012, we changed and added country-specific functionality for Russia. This topic is divided into two sections. The first section outlines the key features that have a broad impact on Russian installations. These features include changes to General ledger, Inventory management, sales and purchase agreements, customer and vendor invoicing, factures, and reporting. The second section describes additional changes to country-specific functionality for Russia. For more information about specific features for Russia, see [TechNet Library for Application Users - Russia](http://go.microsoft.com/fwlink/?linkid=299918).

## Key features for Russia in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3

For installations in Russia, AX 2012 R2 and AX 2012 R3 provides country-specific features that support General ledger updates, fixed asset and depreciation transactions, inventory management, customer and vendor invoicing, factures, and specific requirements for tax and regulatory reporting.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Financial dimensions let you categorize transactions in the general ledger by department, cost center, and other user-defined categories. You can view financial dimensions and other details in the new subledger journal before you post transactions from source documents. You can also set up budget controls for advance reports.

Improved inventory features let you set up a default profile for retail product sales.

Enter details for contracts by using a sales agreement form and a purchase agreement form. You can specify a sales agreement in a customer transaction, such as a customer settlement. You can also specify a purchase agreement for a vendor transaction.

Several changes to customer invoices and vendor invoices, and to the invoice process, let you define the details to post for invoice transactions. You can add lines for categories and expenses that are not associated with purchase orders and sales orders, and allocate order lines to multiple dimensions and ledger accounts. You can also adjust taxes on invoice lines before you post an invoice.

You have more flexibility when you must create, correct, and report factures and any related value-added tax (VAT). You can also set up parameters to automatically update a facture for a retail sales invoice.

By using a new inventory balance turnover report, you can analyze inventory transactions by customer and by vendor.

## Comparison with Microsoft Dynamics AX 2009

These features have changed considerably since AX 2009. AX 2012 R2 and AX 2012 R3 include changes to the following areas:

  - General ledger updates

  - Inventory management

  - Sales and purchase agreements

  - Customer and vendor invoicing

  - Facture updates

  - Reporting

## General ledger updates

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012 R2 and AX 2012 R3</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View, modify, and print transactions on subledger journal lines before you post the transactions to the general ledger. Allocate transaction lines among multiple financial dimensions.</p></td>
<td><p>Not available</p></td>
<td><p>Generate subledger journals from source documents such as invoices, packing slips, and picking lists for customers and vendors. Before you post the transaction amounts to the general ledger, you can view or modify subledger journals by using a new method that is named distribution. This method lets you allocate posting amounts among multiple financial dimensions. You can also change the default ledger account number or financial dimension values, based on user permissions. Additionally, you can distribute amounts on an advance report.</p></td>
<td><p>You can verify information before it is posted.</p></td>
</tr>
<tr class="even">
<td><p>Set up budget control for advance reports.</p></td>
<td><p>Not available</p></td>
<td><p>Use budget control to monitor budget funds on advance reports. Use advance reports to review actual expenses, check the status of budget amounts for expense accounts, and calculate expenses. You can also use advance reports to calculate the open and posted actual expenditures.</p></td>
<td><p>Budget control over advance reports is simplified.</p></td>
</tr>
</tbody>
</table>


## Inventory management

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012 R2 and AX 2012 R3</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up a default inventory profile for retail transactions.</p></td>
<td><p>Not available</p></td>
<td><p>Create an inventory profile that is copied by default to sales orders that are created from transactions in Microsoft Dynamics AX for Retail POS. The default inventory profile that is assigned to the warehouse for the retail store is also used to track inventory movements when the retail statement is calculated and posted.</p></td>
<td><p>It is easier to create sales orders for Retail POS transactions.</p></td>
</tr>
</tbody>
</table>


## Sales and purchase agreements

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012 R2 and AX 2012 R3</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create sales agreements and purchase agreements, and refer to agreements in transactions with customers and vendors.</p></td>
<td><p>You could create contracts.</p></td>
<td><p>Enter contract information by using new sales agreement and purchase agreement forms. Specify sales agreement and purchase agreement details in general journals, transfer orders, and customer and vendor settlements. Generate reports and statements of reconciliation for sales agreements and purchase agreements.</p>
<p>For more information about changes to contracts for Russia, see <a href="deprecated-rus-contracts.md">Deprecated: (RUS) Contracts</a>.</p></td>
<td><p>It is easier to track and report sales agreements for customers and purchase agreements for vendors.</p></td>
</tr>
</tbody>
</table>


## Customer and vendor invoicing

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012 R2 and AX 2012 R3</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Adjust taxes on an invoice line.</p></td>
<td><p>Not available</p></td>
<td><p>Adjust the calculated taxes in a purchase invoice before you post the invoice. Adjust an amount for a specific tax code and also at the level of the invoice line.</p></td>
<td><p>This feature enables more precise tracking of tax amounts that are charged by vendors and provides more accurate costing of purchased items.</p></td>
</tr>
<tr class="even">
<td><p>Create vendor invoices by selecting open purchase orders and purchase lines when you update the facture from the <strong>Purchase order</strong> form. Verify invoices, and then post them as a group.</p></td>
<td><p>Not available</p></td>
<td><p>Create a new invoice, define the invoice account, and select the open purchase orders and purchase lines that you want to invoice together. You can group invoices by using a common code. If one invoice in the payment group is settled, the other invoices in the group are included in the same settlement. You can update and post invoices that are grouped together.</p></td>
<td><p>You have more flexibility when you group purchase invoice lines.</p></td>
</tr>
<tr class="odd">
<td><p>Create a credit correction for a vendor invoice and a free text invoice.</p></td>
<td><p>Not available</p></td>
<td><p>Set up credit correction parameters to post vendor invoices, purchase orders, and free text invoices for a positive amount. You can also receive messages that confirm that you are posting a positive invoice amount that has an accurate correction sign.</p></td>
<td><p>You can correct vendor invoices for both positive and negative amounts.</p></td>
</tr>
<tr class="even">
<td><p>Retrieve purchase orders or product receipts in the <strong>Update facture</strong> form.</p></td>
<td><p>Purchase order or product receipt information was retrieved from the vendor invoice form.</p></td>
<td><p>Retrieve purchase order or product receipt information from the <strong>Update facture</strong> form. From this form, you can view and select the purchase order lines that have the same posting profiles, types of activity, and contract group values by using the retrieve purchase orders or retrieve product receipts process when you post an invoice. From this form, you can also view and select the purchase order lines that have the same posting profiles and types of activity, but that have no contract group values.</p></td>
<td><p>You have additional methods for retrieving purchase information.</p></td>
</tr>
<tr class="odd">
<td><p>Create free text lines in a vendor invoice that are not associated with a purchase order. Create recurring vendor invoices from a free text vendor invoice.</p></td>
<td><p>Not available</p></td>
<td><p>Add lines, which are also known as free text lines, to a vendor invoice. These lines are not associated with a purchase order. You can also create a free text invoice in which no lines are associated with a purchase order. You can save the free text invoice as a template, and then use the template to create recurring vendor invoices for the same amount, tax group, charges, and line amounts.</p></td>
<td><p>Purchases for items and services that are not related to a purchase order are simplified.</p></td>
</tr>
<tr class="even">
<td><p>Create a template for a free text customer invoice. Cancel a free text invoice.</p></td>
<td><p>Not available</p></td>
<td><p>Add lines, which are also known as free text lines, to a customer invoice. These lines are not associated with a sales order. You can also create a free text invoice for a customer in which no lines are associated with a sales order. You can save the free text invoice as a template, and then use the template to create recurring customer invoices for the same amount, tax group, charges, and line amounts. You can cancel a free text invoice instead of creating a corrective invoice.</p></td>
<td><p>Invoice processing for items and services that are not related to a sales order is simplified.</p></td>
</tr>
<tr class="odd">
<td><p>Distribute amounts on a vendor invoice line to multiple ledger accounts.</p></td>
<td><p>Not available</p></td>
<td><p>Allocate the amount on a non-inventoried or category-based purchase invoice line either as an expense to a purchased item or as another expense ledger account. You can also allocate the amount on a vendor invoice line as an expense to a non-inventoried or category-based purchase order line.</p></td>
<td><p>You have flexibility when you record expense amounts on a vendor invoice.</p></td>
</tr>
<tr class="even">
<td><p>Optionally, use a transit expense account when you post a purchase invoice.</p></td>
<td><p>Not available</p></td>
<td><p>Use a transit account to post a purchase invoice before the document date for the vendor invoice is set. When a date for the vendor invoice is selected, the transit account is cleared.</p></td>
<td><p>You can select different dates during vendor balance and inventory posting.</p></td>
</tr>
</tbody>
</table>


## Facture updates

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012 R2 and AX 2012 R3</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Process incoming VAT, and calculate exchange rate adjustments.</p></td>
<td><p>Not available</p></td>
<td><p>Split the lines for selected factures by using a template when you process incoming VAT. You can also copy the exchange rate of the original invoice to the relevant credit note to avoid exchange adjustment calculation when invoices and credit notes are settled. You can process the incoming VAT when a facture is created. The facture is recorded in the <strong>VAT processing log</strong> form.</p></td>
<td><p>You have flexibility when you record fluctuations in exchanges rates on incoming VAT.</p></td>
</tr>
<tr class="even">
<td><p>Automatically update factures for retail sales invoices.</p></td>
<td><p>Not available</p></td>
<td><p>Set up Microsoft Dynamics AX 2012 for Retail parameters so that a facture is automatically updated when the sales invoice and the retail statement are posted.</p></td>
<td><p>It is easier to post factures for retail sales invoices.</p></td>
</tr>
</tbody>
</table>


## Reporting

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012 R2 and AX 2012 R3</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View, analyze, and print information about inventory balance turnover.</p></td>
<td><p>You could view an inventory balance turnover report that had limited filtering options.</p></td>
<td><p>The report was replaced with the <strong>Inventory balance turnover</strong> inquiry. Use the inquiry to view, analyze, and print inventory turnover information for a vendor or a customer. The inquiry provides options for filtering the information. For example, you can view inventory turnover for a specific inventory dimension. Generate balance turnover statements that have collapsed balance output, expanded balance output, or both outputs. Collapsed balance output displays a summarized report of the customer or vendor balance turnovers. Expanded balance output displays complete details of the customer or vendor balance turnovers. For more information about the deprecation of the inventory balance turnover report, see <a href="deprecated-rus-inventory-balance-turnover-report.md">Deprecated: (RUS) Inventory balance turnover report</a> and <a href="deprecated-rus-balance-turnover-statements.md">Deprecated: (RUS) Balance turnover statements</a>.</p></td>
<td><p>You have flexibility when you analyze inventory balance turnover information.</p></td>
</tr>
</tbody>
</table>


## Additional features

For more information about additional country-specific features that we added for Russia, see the tables that apply to your version of the product.

## What’s new in AX 2012 R2

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
<td><p>Data-type tax transactions in the Financial reports generator</p></td>
<td><p>Companies that pay the VAT amount at a rate of 0 (zero) percent must complete all sections of the <strong>VAT declaration</strong> report that are related to export operations. These companies must then submit the report to the sales tax authorities no later than the twentieth day of the month after the close of the tax period. To comply with this requirement, Microsoft Dynamics AX has incorporated additional sections into the layout of the <strong>VAT declaration</strong> report to calculate the VAT amount. For export operations, you can print the <strong>VAT declaration</strong> report for all sections. The information that is available for each section is grouped by operation code. Entries from an operation code list that is controlled by the tax authority are defined for each section, based on column positions. For more information about the <strong>VAT declaration</strong> report, see <a href="rus-incoming-and-outgoing-vat-data-on-the-vat-declaration-report.md">(RUS) Incoming and outgoing VAT data on the VAT declaration report</a>.</p></td>
</tr>
<tr class="even">
<td><p>Calculate cost for work in process (WIP) and finished goods.</p></td>
<td><p>In accordance with Russian legislation, companies must calculate the cost of WIP at the end of each reporting period. The production order cost is distributed among WIP, by-products, defective products, and finished goods.</p>
<p>You can perform the following tasks:</p>
<ul>
<li><p>Use the by-product journal to register by-products and defective products that are generated under a production order.</p></li>
<li><p>Create and post storno transactions to the general ledger when the status of a production order is updated and its cost is calculated.</p></li>
<li><p>Calculate the cost of a production order by using either the normative method, in which the WIP and by-product costs are calculated by using per-operation standard costs, or the proportional allocation method, in which the WIP and by-product costs are calculated by using actual costs.</p></li>
</ul>
<p>For more information about cost calculations, see <a href="rus-calculating-costs-for-wip-and-finished-goods.md">(RUS) Calculating costs for WIP and finished goods</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Process incoming VAT, and calculate exchange adjustments.</p></td>
<td><p>You can split all the lines for selected factures by using a template when you process incoming VAT. You can also copy the exchange rate of the original invoice to the relevant credit note to avoid exchange adjustment calculation during invoice and credit note settlements. You can process the incoming VAT when a facture is created. The facture is recorded in the <strong>Incoming VAT</strong> processing log form.</p></td>
</tr>
<tr class="even">
<td><p>Bank and address information for payments to foreign bank accounts</p></td>
<td><p>Payments that are made to vendors by using payment orders or payment requests must include additional information about the vendor bank account if the vendor uses a foreign bank to receive payments. This information can include the bank code, the bank name, the Society for Worldwide Interbank Financial Telecommunication (SWIFT) code of the foreign bank, the foreign bank account number of the vendor, and the address of the payer. For more information, see <a href="rus-set-up-an-intermediate-bank-account-for-a-foreign-vendor.md">(RUS) Set up an intermediate bank account for a foreign vendor</a>.</p>
<p>When you make payments to the foreign bank account of a vendor, the vendor must register a bank account with a Russian bank. This bank account can be assigned as an intermediate bank account between the payer and the vendor. You can generate a payment order for the payments, and then enter the details of the vendor bank account and the vendor account that the payments are made to. For more information, see <a href="rus-set-up-an-intermediate-bank-account-for-a-foreign-vendor.md">(RUS) Set up an intermediate bank account for a foreign vendor</a>.</p>
<p>For transactions that involve payment returns to a foreign customer, you can set up a customer bank account to receive the returned payments, and then generate a customer payment order that includes the bank and address of the payer. For more information, see <a href="rus-set-up-a-foreign-bank.md">(RUS) Set up a foreign bank</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Storno transactions in transfer orders</p></td>
<td><p>You can use storno transactions to post corrections in transfer orders that are made by using shipments and receipt orders. You can also use storno transactions for the following kinds of corrections:</p>
<ul>
<li><p>Correct errors that are made during processing of shipments or receipt orders</p></li>
<li><p>Correct transactions that involve goods that were shipped from the source warehouse and later returned</p></li>
</ul>
<p>For more information about how to post a storno transaction in a transfer order, see <a href="rus-create-and-post-a-storno-transfer-journal.md">(RUS) Create and post a storno transfer journal</a>.</p></td>
</tr>
<tr class="even">
<td><p>Cancel free text invoices without creating corrective invoices.</p></td>
<td><p>You can choose not to generate corrected free text invoices when you cancel incorrect invoices that were previously posted. A canceling invoice is created that has a negative amount that equals the amount of the original posted invoice.</p></td>
</tr>
<tr class="odd">
<td><p>Updates to purchase order and sales order reports, and to the allocation of miscellaneous charges for category-based order lines</p></td>
<td><p>You can allocate miscellaneous charges from a purchase order header to a category-based purchase order line, based on the weight or volume information on the lines. You can also print the weight and volume information for the category-based order lines in the following reports:</p>
<ul>
<li><p>TORG-1</p></li>
<li><p>TORG-12</p></li>
<li><p>Bill of lading 1-T</p></li>
</ul>
<p>For more information about how to allocate charges, see <a href="rus-allocate-charges-according-to-weight-and-volume-of-goods.md">(RUS) Allocate charges according to weight and volume of goods</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to currency valuation</p></td>
<td><p>The following updates have been made to currency valuation:</p>
<ul>
<li><p>You can enter currency valuation accounts and tax dimensions for the accounting currency in the <strong>Currency parameters</strong> form, and for specified currencies in the <strong>Currency revaluation accounts</strong> form.</p></li>
<li><p>The periodic exchange adjustment of advance holders considers the unrealized profit and loss that is specified on the <strong>Advance holders</strong> tab.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Changes to the status of company bank accounts for the Russian Federation</p></td>
<td><p>The status of a company's bank account determines the bank account's reconciliation, transaction posting, and statement generation processes. The status of a bank account can be inactive for all transactions or only for new transactions that are created after the account is inactivated. When the status of the bank account is inactive for all transactions, you cannot post any outgoing or incoming payments and payment receipt transactions. If the status is inactive for new transactions, you cannot post incoming payments, but you can post outgoing payments for transactions that were posted when the account was active.</p>
<p>You cannot change the bank account status to inactive if the account has any vendor transactions that are open. You cannot use the <strong>Transit account</strong> option to change the date of a posted transaction when you reconcile a bank account that is inactive. You cannot generate incoming or outgoing transaction statements for bank accounts that are inactive. For more information about the status of a bank account, see <a href="rus-changes-to-company-bank-accounts.md">(RUS) Changes to company bank accounts</a>.</p></td>
</tr>
<tr class="even">
<td><p>New requirements for bank payment orders</p></td>
<td><p>In accordance with the regulations of the Ministry of Finance of the Russian Federation, changes have been made to the printed form of bank payment orders. A bank payment order that is printed for a customer that is associated with a customs authority also contains the customs authority code. For more information about the changes, see <a href="rus-generate-a-bank-payment-order-for-a-customs-authority.md">(RUS) Generate a bank payment order for a customs authority</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Non-recoverable VAT amounts as part of the budget</p></td>
<td><p>Materials and fixed assets that are acceptable as deductions and used in VAT-free activities are subject to VAT amount restoration. A company that conducts operations that are subject to VAT, and that are tax exempt, can deduct all incoming VAT amounts if the company’s share of expenses on tax-exempt operations is not more than 5 percent of the total production cost. The VAT amount that is deducted on goods, materials, or fixed assets that are not subject to VAT can be recovered or restored by exporting the shipment of goods, and by using fixed assets in export production.</p>
<p>VAT amounts can also be restored for the following transactions:</p>
<ul>
<li><p>Write-off of a fixed asset.</p></li>
<li><p>Disposal because of fire.</p></li>
<li><p>Transfer to authorized capital.</p></li>
<li><p>The cost of goods, such as work or services, can be calculated by including or excluding VAT, depending on the revenue calculation method for the VAT amount restoration.</p></li>
</ul>
<div class="alert">

> [!NOTE]
> <P>The amount that is specified during realization on export transactions excludes VAT.</P>


</div>
<p>The restored VAT amount can be canceled for the current period. The restored VAT processing and cancellation log is displayed in the <strong>VAT processing</strong> log form. During confirmation of the export process, any VAT amounts that were restored earlier can be reimbursed. Companies can reimburse a VAT amount on export factures under these conditions:</p>
<ul>
<li><p>Confirmation on export factures was not received in time.</p></li>
<li><p>Confirmation on export factures was not received, and the confirmation term has expired in the current period.</p></li>
</ul>
<p>For more information about VAT recovery, see <a href="rus-calculate-restored-vat-and-revenue-amounts.md">(RUS) Calculate restored VAT and revenue amounts</a>.</p></td>
</tr>
<tr class="even">
<td><p>Detailed balance turnover report for Russia</p></td>
<td><p>You can view detailed balances for settled transactions in balance turnover reports in both Accounts receivable and Accounts payable. From the <strong>Inventory balance turnover</strong> form, you can generate balance turnover details for customers and vendors, general ledger accounts, and contracts for settled transactions. You can generate balance turnover statements that have collapsed balance output, expanded balance output, or both collapsed and expanded balance output. Collapsed balance output displays a summarized report of the customer or vendor balance turnovers. Expanded balance output displays complete details of the customer or vendor balance turnovers.</p>
<p>For more information about the balance turnover report, see <a href="rus-generate-the-inventory-balance-turnover-report.md">(RUS) Generate the inventory balance turnover report</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Corrective and revised factures</p></td>
<td><p>You can create and print corrective and revised factures that are based on credit notes, corrective invoices, and tax correction transactions. You can also revise either the lines or header of an existing facture. All the corrections and revisions of a facture are made in a specific order. You can view the details of the changes and the interim state of the facture.</p>
<p>You can also print the following documents in an updated report format:</p>
<ul>
<li><p>Original facture</p></li>
<li><p>Corrective facture</p></li>
<li><p>Revised facture</p></li>
<li><p>Sales book</p></li>
<li><p>Purchase book</p></li>
<li><p>Facture register</p></li>
</ul>
<p>For more information about how to create and print factures, see <a href="rus-create-and-print-factures-for-vat-deductions.md">(RUS) Create and print factures for VAT deductions</a>.</p></td>
</tr>
<tr class="even">
<td><p>Multiple worker table numbers for an advance holder</p></td>
<td><p>The personnel number is a unique code that is used to identify a worker. A worker can be an employee or a contractor. An employee or a contractor, in turn, can also be an advance holder. A worker can hold several positions in the organization. Transactions can be posted by using advance holder accounts. To manage and track these transactions, you can define a worker table number for each position that a worker holds. You can define multiple worker table numbers for the personnel number of a worker.</p></td>
</tr>
<tr class="odd">
<td><p>Bonus depreciation for fixed assets after major repairs</p></td>
<td><p>In accordance with Russian regulations, when major repair work is performed on a fixed asset, bonus depreciation applies to the asset on or after the date of the major repair transaction.</p>
<p>You can create a major repair transaction for a fixed asset, and specify the bonus depreciation and bonus start date. The start date of the bonus depreciation can be the same as the major repair transaction date or the next depreciation date.</p>
<p>For more information about bonus depreciation for fixed assets, see <a href="rus-about-bonus-depreciation-for-fixed-assets-after-major-repairs.md">(RUS) About bonus depreciation for fixed assets after major repairs</a>. For more information about how to calculate bonus depreciation, see <a href="rus-calculate-a-bonus-depreciation.md">(RUS) Calculate a bonus depreciation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Adjust taxes on an invoice line.</p></td>
<td><p>You can adjust the calculated taxes on an invoice line before posting.</p></td>
</tr>
<tr class="odd">
<td><p>Post storno transactions for adjustments to the inventory cost value.</p></td>
<td><p>You can post storno transactions for adjustments to the inventory cost value that are created during inventory closing. When you close the inventory, you can also post the minimum inventory cost adjustments to rounding-off accounts instead of profit and loss accounts.</p></td>
</tr>
<tr class="even">
<td><p>Receipt deferral transactions and updates to the manual write-off method for deferrals</p></td>
<td><p>By using the manual write-off method for deferrals, you can now specify a write-off amount or percentage in the <strong>Writing off methods</strong> form. For deferrals that have a status of <strong>Scheduled</strong>, you can set the <strong>Transaction type</strong> field to <strong>Receipt</strong> to create transactions in a deferral journal.</p></td>
</tr>
<tr class="odd">
<td><p>Calculation of customs payments</p></td>
<td><p>Russian organizations must calculate customs payments for any foreign trade activity. You can now create and post a customs journal to calculate payments for customs clearance of imported or exported goods. A customs payment includes the calculated customs duties and taxes that are levied on the goods that are involved in foreign trade. Customs payments are calculated and paid to the customs authority on the basis of Customs Nomenclature Code of the Foreign Economic Activity (TN VED) codes. TN VED codes are customs codes that are used for foreign trade. These codes include all details of the imported or exported goods.</p>
<p>You can perform the following tasks:</p>
<ul>
<li><p>Post the liability of the customs authority or the customs broker.</p></li>
<li><p>Revalue the cost price of import goods.</p></li>
<li><p>Account for customs cargo declarations (GTDs) as inventory dimensions.</p></li>
<li><p>Include GTDs and customs value correction (KTS) in purchase books.</p></li>
<li><p>Account for transfers of property ownership.</p></li>
</ul>
<p>For more information about how to set up customs payments, see <a href="rus-set-up-a-charges-code-for-customs-payments.md">(RUS) Set up a charges code for customs payments</a>.</p></td>
</tr>
<tr class="even">
<td><p>Sort inventory adjustments and inventory settlements by charges code.</p></td>
<td><p>You can sort inventory adjustments and inventory settlements by charges code. Cost adjustments and settlements that are made for an item are sorted by charges code and saved during inventory closing. You can also view the structure of the charges that are accrued by item, receipt cost, types of charges that are adjusted to the purchase invoice, and cost adjustments in inventory transactions.</p></td>
</tr>
<tr class="odd">
<td><p>Create inventory profiles to determine the movement of items and balance turnover.</p></td>
<td><p>An inventory profile is used to track and report the movement of items and the accounting of on-hand inventory quantities, based on the types of activity that the company engages in. Because the general ledger transactions that correspond to inventory movements depend on the inventory profiles, you can ascertain the balance turnover of inventory and financial accounting by the types of activity. For more information about how to set up an inventory profile, see <a href="rus-set-up-an-inventory-profile.md">(RUS) Set up an inventory profile</a>.</p>
<p>The movements and on-hand quantities of a particular item that has various inventory profiles or types of activity are tracked by using inventory dimensions in inventory accounting and general ledger accounts in financial accounting.</p></td>
</tr>
<tr class="even">
<td><p>Transfer proprietary rights for goods that are in transit.</p></td>
<td><p>When you ship goods to a customer and post a sales invoice for the shipment, the ownership (proprietary rights) of the goods is transferred to the customer. If, for some reason, such as the terms of a trade agreement, the proprietary rights cannot be transferred on the date of shipment, you can indicate this fact in the sales invoice. The customer becomes liable for the goods only when ownership is transferred. If the transfer is delayed, you remain responsible for calculating and paying sales tax at the time of shipment, in accordance with Russian legislation. Russian law requires that you calculate and pay sales tax on goods that are shipped to a customer, and that you register goods that are in transit in a specific general ledger account.</p>
<p>You can perform the following tasks when the transfer of proprietary rights is delayed:</p>
<ul>
<li><p>Create a sales invoice that indicates the delayed property transfer.</p></li>
<li><p>Calculate the sales tax that is payable for the shipped goods.</p></li>
<li><p>Store the shipped goods in a transit warehouse for the customer, pending delayed property transfer.</p></li>
<li><p>Register a transfer of proprietary rights.</p></li>
<li><p>Set up and allocate miscellaneous charges that are associated with the shipment and transfer.</p></li>
</ul>
<p>You can reverse a shipment until the ownership is transferred to a customer. When you reverse a shipment, the goods are returned to the warehouse, and the sales invoice is canceled.</p>
<p>You can also set up revenue, consumption, and transit general ledger accounts to post miscellaneous sales charges for the shipped goods. You can also allocate and post miscellaneous charges for a sales invoice.</p>
<p>For more information, see <a href="rus-set-up-the-posting-type-and-number-sequences-to-transfer-proprietary-rights.md">(RUS) Set up the posting type and number sequences to transfer proprietary rights</a>.</p></td>
</tr>
<tr class="odd">
<td><p>TORG-12 and M-15 invoice formats for Russia</p></td>
<td><p>Customer invoices and vendor invoices can be posted and printed in the TORG-12 and M-15 formats. You can use the TORG-12 format for invoices to confirm sales and the delivery of goods to a customer. You can use the M-15 format for invoices for non-sales agreements. After posting, you can print the invoices in Microsoft Excel.</p>
<p>For more information about the TORG-12 report, see <a href="rus-print-the-torg-12-report.md">(RUS) Print the TORG-12 report</a>.</p></td>
</tr>
<tr class="even">
<td><p>Allocate miscellaneous charges.</p></td>
<td><p>You can select an expense invoice to allocate miscellaneous charges to other invoices that have the same vendor account.</p></td>
</tr>
<tr class="odd">
<td><p>Updates to purchase invoices</p></td>
<td><p>You can create a new invoice, define the invoice account, and select the open purchase orders and purchase lines to invoice together. You can group invoices by using a common code. If one invoice in the payment group is settled, the other invoices in the group are included in the same settlement. You can update and post invoices that are grouped together.</p>
<p>For more information about how to set up an allocation, see <a href="rus-create-and-post-a-vendor-invoice-to-allocate-charges.md">(RUS) Create and post a vendor invoice to allocate charges</a>.</p>
<p>For Russia, you can create invoices by selecting open purchase orders and purchase lines when you update the facture from the <strong>Purchase order</strong> form. You can filter purchase lines by the kind of activity and the posting profile. Only purchase lines that have the same kind of activity and posting profile can be grouped. You can verify these invoices and then post them together.</p></td>
</tr>
<tr class="even">
<td><p>Calculation of depreciation and fixed asset tax registers for vehicles and realty</p></td>
<td><p>Fixed assets, such as vehicles and realty, can be depreciated beginning on the date when they are registered. You can also calculate the values in assessed tax and transport tax registers, based on the fixed asset registration date and the date when the asset was removed from the register. For more information, see <a href="rus-set-up-fixed-asset-parameters-for-vehicles-and-realty.md">(RUS) Set up fixed asset parameters for vehicles and realty</a>.</p>
<p>You can specify the registration date for assets of the <strong>Vehicle</strong> and <strong>Realty</strong> types in the <strong>Date of the registration</strong> field in the <strong>Fixed assets</strong> form. Vehicles are included in the transport tax register beginning on their registration date and remain in the register until they are removed from it. Fixed assets of both types are included in the assessed tax register beginning on their registration date. For more information, see <a href="rus-set-up-the-depreciation-starting-date-for-vehicles-and-realty.md">(RUS) Set up the depreciation starting date for vehicles and realty</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Retrieve purchase orders or product receipts in the <strong>Update facture</strong> form.</p></td>
<td><p>You can retrieve information about purchase orders or product receipts from the vendor invoice form. For Russia, you can now also retrieve this information from the <strong>Update facture</strong> form, which is based on the <strong>Posting invoice for payment</strong> form. You can view and select the purchase order lines that have the same posting profiles, the same kind of activity, and the same contract group values from the <strong>Update facture</strong> form by using the retrieve purchase orders or retrieve product receipts during invoice posting. You can also view and select the purchase order lines that have the same posting profiles and the same kind of activity, but that have no contract group values, by using the retrieve purchase orders or retrieve product receipts during invoice posting. For more information, see <a href="https://technet.microsoft.com/library/jj889412(v=ax.60)">(RUS) Update facture (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Inventory adjustments that use offset accounts and storno transactions</p></td>
<td><p>When you post inventory adjustments, you can specify an offset account to record the monetary details of adjustment postings. You can also post negative adjustments by using storno transactions. You can specify an adjustment calculation method to calculate the total adjustment amount and then specify a ledger account to record the total adjustment amount.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to the inventory management process for Russia</p></td>
<td><p>In Microsoft Dynamics AX, enhancements to the inventory management process include the following requirements for Russia:</p>
<ul>
<li><p>Use the <strong>GTD number</strong> or <strong>Owner</strong> inventory dimension as a picking dimension value in the <strong>Inventory picking</strong> form.</p></li>
<li><p>Print the details of the <strong>GTD number</strong>, <strong>Inventory profile</strong>, or <strong>Owner</strong> inventory dimension on the kanban card and in the Lean picking list.</p></li>
<li><p>Post storno general ledger transactions for miscellaneous charge adjustments and purchase overheads to reconcile the general ledger entries with the inventory.</p></li>
<li><p>Identify inventory postings that are not posted to the ledger in the dual warehouse posting layer.</p></li>
<li><p>Post the purchase/production indirect costs in the dual warehouse posting layer to reconcile the general ledger with the inventory.</p></li>
<li><p>Post by-product receipts from production orders in the dual warehouse posting layer to reconcile the general ledger with the inventory.</p></li>
<li><p>View inventory settlements in a secondary currency by using the <strong>Cost explorer</strong> form.</p></li>
<li><p>Post project inventory transaction adjustments in the dual warehouse posting layer to reconcile the general ledger with inventory.</p></li>
<li><p>Use unlimited financial dimensions in all forms and reports in the SCM area.</p></li>
<li><p>Enable inventory dimension inheritance in inventory transfers for all tracking inventory dimensions.</p></li>
<li><p>Restrict calculations of purchase overhead for purchase receipts that have specific values for the <strong>Inventory profile</strong> inventory dimension.</p></li>
</ul>
<p>The Inventory turnover inquiry also uses unlimited financial dimensions.</p>
<p>For more information about inventory management, see <a href="rus-working-with-inventory-and-warehouse-management.md">(RUS) Working with Inventory and warehouse management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to the calculation of write-off time for deferrals</p></td>
<td><p>In accordance with Russian legislation, the write-off time for deferrals must be calculated by using the factor that is used during the fixed asset depreciation. When you create a transaction for partial write-off or disposal of a fixed asset, if the transaction causes a loss, the transaction details are posted to a deferral account. This account contains the calculated value of the loss and the write-off time. The write-off time is calculated by using the useful life of the depreciated asset, the actual period of use before the asset’s disposal, and the fixed asset depreciation factor. For more information, see <a href="https://technet.microsoft.com/library/jj853189(v=ax.60)">(RUS) Factors for deferrals writing off (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Accounting for working clothes, special rigging, and not valuable fixed assets (NVFAs)</p></td>
<td><p>You can account for the following items:</p>
<ul>
<li><p>Working clothes and special rigging assets – You can create a Working clothes or Special rigging issue card for working clothes and special rigging assets that are issued to employees. The useful life cycle period for a working clothes item or special rigging item begins when the item is written off from a warehouse and issued to an employee, and ends after the specified period of use for that item. The useful lifetime for each item is specified in months.</p></li>
<li><p>NVFAs – If the purchase price of a fixed asset is less than the value that is specified in the <strong>Max cost of the NVFA</strong> field in the <strong>Fixed asset parameters</strong> form, the item is considered an NVFA. You cannot specify a fixed asset inventory number for this kind of item in the <strong>Purchase order</strong> form. You cannot register an NVFA in the <strong>Not valuable FAs</strong> form until the purchase order process is completed. Depreciation is calculated for each not valuable and high-wearing item.</p>
<p>For more information about how to account for working clothes, special rigging, and NVFAs, see <a href="rus-about-nvfas-working-clothes-and-special-rigging-accounting.md">(RUS) About NVFAs, working clothes, and special rigging accounting</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Set up and copy financial report layouts by using the Financial reports generator for Russia</p></td>
<td><p>You can set up financial report layouts by using the Financial reports generator, and you can copy the report layout settings of one legal entity to another. You can also set up multiple report layouts and generate financial reports that are based on the specified report layouts. For more information about how to set up reports, see <a href="rus-setting-up-the-financial-reports-generator.md">(RUS) Setting up the Financial reports generator</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Vendor invoices that are not associated with a purchase order and recurring invoices</p></td>
<td><p>You can create vendor invoices that are not associated with a purchase order. The invoice and invoice lines are included in the associated facture, and the following information is updated for each invoice line:</p>
<ul>
<li><p>The invoice amount can be split in incoming VAT processing.</p></li>
<li><p>If the invoice account is inherited, the exchange adjustments for the invoice line are created by using the corresponding account.</p></li>
<li><p>If the invoice account is inherited, the advance adjustments for the invoice line are created by using the corresponding account.</p></li>
<li><p>The amounts on the line are posted to the general ledger by using the posting profile that is used in the invoice.</p></li>
</ul>
<p>You can also print a recurring invoice and create a facture.</p>
<p>The facture for customers and vendors is created when the invoice is posted and after invoice posting.</p>
<p>For more information, see <a href="rus-creating-an-invoice-that-is-not-related-to-a-purchase-order.md">(RUS) Creating an invoice that is not related to a purchase order</a>.</p></td>
</tr>
<tr class="even">
<td><p>Changes to the calculation of amount differences and exchange adjustments for prepayments</p></td>
<td><p>In accordance with Russian legislation for tax accounting, if a vendor makes prepayments, you must not calculate the exchange adjustment for those prepayments in tax accounting registers.</p>
<p>You can specify whether to calculate the amount difference for the prepayments in the tax accounting registers.</p></td>
</tr>
<tr class="odd">
<td><p>Distribution of subledger lines</p></td>
<td><p>Subledger journal lines are accounting entries that are posted to the general ledger by using the General journal. You can generate subledgers from source documents such as invoices, packing slips, and picking lists for customers and vendors. Before you post the voucher information to the general ledger, you can view or edit subledger journals by using a new method that is named distribution. This method lets you allocate posting amounts among multiple financial dimensions, and change the default ledger account number or financial dimension values based on user permissions.</p>
<p>In Russia, an advance report is used to report travel expenses that an employee incurs during a business trip. You can distribute the expense amount among various ledger dimensions. You can view the ledger entries and verify the distribution of the expense amount.</p>
<p>For more information about subledger journals, see <a href="rus-about-accounting-distributions-and-subledger-journals.md">(RUS) About accounting distributions and subledger journals</a>.</p></td>
</tr>
<tr class="even">
<td><p>Import currency exchange rates from the Central Bank of the Russian Federation (CBRF) website.</p></td>
<td><p>You can import currency exchange rates from the CBRF website into Microsoft Dynamics AX 2012. You can import these rates to meet a specific and immediate requirement, or you can periodically import the rates as a batch. You can also set up the coefficient factors that are used when currency exchange rates are imported.</p>
<p>For more information, see <a href="rus-import-exchange-rates-from-the-cbrf-website.md">(RUS) Import exchange rates from the CBRF website</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Post invoices based on packing slips.</p></td>
<td><p>The invoices and factures for a purchase order or a sales order can be posted at the same time.</p>
<p>For more information, see <a href="rus-update-factures-and-post-invoices-for-open-purchase-orders.md">(RUS) Update factures and post invoices for open purchase orders</a>.</p></td>
</tr>
<tr class="even">
<td><p>Non-linear depreciation</p></td>
<td><p>You can use non-linear depreciation to mark accrued depreciation for the previous year for taxation purposes. Monthly depreciation is calculated as follows:</p>
<p>Remaining value of the asset * Depreciation rate</p>
<p>For more information, see <a href="rus-linear-and-non-linear-depreciation-methods.md">(RUS) Linear and non-linear depreciation methods</a> and <a href="rus-set-up-depreciation-methods.md">(RUS) Set up depreciation methods</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Bailment process and calculation of storage service amounts</p></td>
<td><p>Bailment is the act of transferring items to a company or individual for storage. The company or individual that owns the items is the bailor, and the company or individual that stores the items in warehouses is the bailee. During the bailment process, proprietary rights for the items are not transferred from the bailor to the bailee. Therefore, the bailee must track and manage these items in a separate account. After a period that the bailor and bailee agree on, the bailee returns the items to the bailor and charges a storage service amount.</p>
<p>In accordance with Russian legislation, bailees must generate the following reports when they store a bailor's items:</p>
<ul>
<li><p>Acceptance report in storage (MX-1)</p></li>
<li><p>Counting list (INV-5) report</p></li>
<li><p>Return report from storage (MX-3)</p></li>
</ul>
<p>You can generate these reports as Excel worksheets. You can also set up search priorities and methods to calculate the storage service amount for the items that are stored in a warehouse.</p>
<p>For more information, see <a href="rus-calculation-of-the-storage-service-amount-for-items.md">(RUS) Calculation of the storage service amount for items</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate and print a transportation invoice and a job ticket, based on a bill of lading.</p></td>
<td><p>You can generate and print a transportation invoice and a job ticket for a document, such as a sales order or transfer order that is created for an automobile carrier.</p>
<p>For more information, see <a href="rus-about-transportation-invoices-and-job-tickets-that-are-based-on-bills-of-lading.md">(RUS) About transportation invoices and job tickets that are based on bills of lading</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Ledger correspondence for Russia</p></td>
<td><p>All general ledger postings for Russia are made under the correspondence rule, where a one-to-one relationship is established between a debit transaction and a credit transaction. Correspondence of ledger transactions is enabled for purchase overheads and for all general ledger postings in Lean manufacturing.</p>
<p>For more information, see <a href="rus-about-correspondence.md">(RUS) About Correspondence</a>.</p></td>
</tr>
<tr class="even">
<td><p>Exchange adjustment and profit/loss calculation on the Remittance en route account</p></td>
<td><p>When a company sells or transfers rubles, the Federal Bank exchange rate can change during the transaction process if the transaction occurs on multiple dates. In this case, you must calculate the exchange adjustment for the Remittance en route account. If the bank exchange rate does not equal the Federal Bank exchange rate for the purchase or sale of a foreign currency, a profit or loss transaction is created. You can start and generate payments for a conversion (purchase or sale) or transfer transactions for foreign currency from Accounts payable. When you create a conversion or transfer transactions, an exchange adjustment is calculated for the Remittance en route account, and the profit or loss is calculated.</p>
<p>For more information, see <a href="rus-create-profit-or-loss-transactions-for-a-currency-conversion-or-transfer-and-exchange-adjustment.md">(RUS) Create profit or loss transactions for a currency conversion or transfer and exchange adjustment</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Advance adjustment for advance holders</p></td>
<td><p>Exchange adjustments on advance payments that were issued or received in currency no longer have to be calculated in business accounting.</p>
<p>When you settle advance payments and advance reports, the advance adjustment transaction is created as a continuation of the advance report, based on the setup in the <strong>General ledger parameters</strong> form and the <strong>Advance adjustment parameters</strong> form. The advance adjustment transaction is displayed in the <strong>Advance holder transactions</strong> form. The amounts on the advance report are based on the exchange rate on the advance payment date, not the posting date.</p>
<p>For more information, see <a href="rus-set-up-general-ledger-parameters-for-exchange-adjustment.md">(RUS) Set up general ledger parameters for exchange adjustment</a> and <a href="rus-set-up-advance-adjustment-parameters-for-advance-holders.md">(RUS) Set up advance adjustment parameters for advance holders</a>.</p></td>
</tr>
<tr class="even">
<td><p>Fixed asset transfers for Russia</p></td>
<td><p>By using the transfer history process for fixed assets that belong to Russian legal entities, you can perform the following tasks:</p>
<ul>
<li><p>Assign a new lifetime to a fixed asset.</p></li>
<li><p>Assign a new location to a fixed asset.</p></li>
<li><p>Assign a new person who is in charge of the fixed asset.</p></li>
<li><p>Assign tax allowances to ground area fixed assets.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Dimension control for settlements</p></td>
<td><p>Dimension control settlement helps you accurately manage and analyze accounting with vendors, customers, and advance holders by financial dimension.</p>
<p>For more information, see <a href="rus-set-up-a-dimension-set-for-dimensions-control-for-settlements.md">(RUS) Set up a dimension set for dimensions control for settlements</a>.</p></td>
</tr>
<tr class="even">
<td><p>Counting list of purchased items that are in transfer</p></td>
<td><p>In accordance with Russian legislation, companies (owners) that purchase items must generate a <strong>Counting act (INV-6)</strong> report to track items when those items are transferred to the company’s warehouse.</p>
<p>You can generate the <strong>Counting act (INV-6)</strong> report as an Excel worksheet. You must use the <strong>Inventory profile</strong> and <strong>Owner</strong> dimensions to generate the <strong>Counting act (INV-6)</strong> report. You can also apply the <strong>Warehouse</strong> and <strong>Batch number</strong> dimensions to this report. The <strong>Counting act (INV-6)</strong> report contains the following information:</p>
<ul>
<li><p>The name of the vendor</p></li>
<li><p>The identification numbers of the officials who are involved in the item counting process</p></li>
<li><p>The description, ID, count, dimensions, and total cost of the items that are in transfer</p></li>
<li><p>The names, numbers, and issue dates of invoices, bills of lading, and receipts that accompany the items during transfer</p></li>
<li><p>The starting and ending dates of the inventory count</p></li>
<li><p>The date and number of the inventory counting order</p></li>
</ul>
<p>For more information, see <a href="rus-generate-a-counting-act-inv-6-report.md">(RUS) Generate a Counting act (INV-6) report</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Generate the <strong>NVFA accounting card (No. MB-2)</strong>, <strong>NVFA Act on disposal (No. MB-4)</strong>, and <strong>NVFA Statement of writing-off (No. MB-8)</strong> reports.</p></td>
<td><p>You can use the following updated reports for NVFAs:</p>
<ul>
<li><p>NVFA accounting card (No. MB-2) – Generate a unified NVFA accounting card (No. MB-2) to account for the issue of working clothes, special rigging, and NVFAs to employees for long-term use.</p></li>
<li><p>NVFA Statement of disposal (No. MB-4) – Generate a unified NVFA statement of disposal (No. MB-4) to document the disposal of working clothes, special rigging, and NVFAs.</p></li>
<li><p>NVFA Statement of writing-off (No. MB-8) – Generate a unified NVFA statement of writing-off (No. MB-8) to document the write-off of working clothes, special rigging, and NVFAs.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-generate-the-nvfa-accounting-card-no-mb-2-for-nvfas-special-rigging-and-working-clothes.md">(RUS) Generate the NVFA accounting card (No. MB-2) for NVFAs, special rigging, and working clothes</a></p></li>
<li><p><a href="rus-generate-a-write-off-transaction-and-print-the-nvfa-statement-of-disposal-no-mb-4-from-the-fixed-asset-journal.md">(RUS) Generate a write-off transaction and print the NVFA statement of disposal (No. MB-4) from the fixed asset journal</a></p></li>
<li><p><a href="rus-generate-the-nvfa-statement-of-writing-off-no-mb-8-from-the-working-clothes-special-rigging-or-not-valuable-fas-forms.md">(RUS) Generate the NVFA statement of writing-off (No. MB-8) from the Working clothes, Special rigging, or Not valuable FAs forms</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Enhancements to sales orders and purchase orders, and product receipt corrections and packing slip corrections, for the Russian Federation</p></td>
<td><p>You can create and print new versions of the receipt statement reports (TORG-1, TORG-2, TORG-3, M-4, and M-7) when you correct purchase order receipts. You can retain a receipt statement’s document type and number for a corrected purchase order receipt. You can also update the deviation quantity of the corrected purchase order receipt.</p>
<p>You can specify the customs declaration ID and country/region of origin for category-based sales order and purchase order lines. This information is transferred to the facture journal.</p>
<p>When you create and post a sales return order, the <strong>GTD number</strong> and <strong>Owner</strong> dimensions for the returned product must be the same as the <strong>GTD number</strong> and <strong>Owner</strong> dimensions on the referenced invoice line. When you correct a sales packing slip, the <strong>GTD number</strong> and <strong>Owner</strong> dimensions for the corrected sales packing slip must be the same as the <strong>GTD number</strong> and <strong>Owner</strong> dimensions on the original sales packing slip.</p>
<p>You can specify the contract group and contract registration number (DVR) for the trade agreements when you select a trade agreement in the trade agreement journal. You can modify only those trade agreements that are related to a corresponding contract group and DVR.</p>
<p>You cannot use non-inventoried or category-based order lines when you perform the following tasks:</p>
<ul>
<li><p>Receive or return goods for a bailment.</p></li>
<li><p>Sell goods for a bailment.</p></li>
<li><p>Place purchased goods in transit.</p></li>
<li><p>Create a customs journal for import and export.</p></li>
</ul>
<p>You can allocate the amount on a non-inventoried or category-based purchase invoice line as an expense to a purchased item or as another expense. You can also allocate the amount on a vendor invoice line as an expense to a non-inventoried or category-based purchase order line.</p>
<p>For more information, see <a href="rus-correct-a-product-receipt-and-print-the-receipt-statement-report.md">(RUS) Correct a product receipt and print the receipt statement report</a>.</p></td>
</tr>
<tr class="odd">
<td><p>VAT for export trade</p></td>
<td><p>You can now perform the following tasks:</p>
<ul>
<li><p>Define the period of export confirmation and tax codes for export deliverables that are taxable at 0 (zero) percent VAT.</p></li>
<li><p>Specify the export date, expiration date, and confirmation date.</p></li>
<li><p>Specify the operation types for the export factures.</p></li>
<li><p>Set the VAT processing parameters, and process outgoing VAT operations for the current period.</p></li>
<li><p>Define tax reporting information, and calculate the penalty of any overdue amount from the export confirmation.</p></li>
</ul>
<p>For more information, see <a href="rus-create-an-export-facture.md">(RUS) Create an export facture</a>.</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable and accounts payable invoices for Russia</p></td>
<td><p>You can print customer invoices and the corresponding acceptance reports for a customer from the <strong>Open customer invoices</strong> and <strong>All free text invoices</strong> list pages. You can print the invoices and acceptance reports that have been generated over a period.</p>
<p>You can correct and post a free text invoice, view the related invoices, and navigate between the parent and corrected invoices. The invoice date for the corrected invoice must be in the open sales book period. The canceled invoice is posted to the <strong>General journal</strong> as a storno transaction. The <strong>Corrective document</strong> field for the new invoice is updated with the original invoice date and number.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-create-and-update-a-facture-for-a-corrected-free-text-invoice.md">(RUS) Create and update a facture for a corrected free text invoice</a></p></li>
<li><p><a href="rus-create-and-update-a-facture-for-a-corrected-credit-note-invoice.md">(RUS) Create and update a facture for a corrected credit note invoice</a></p></li>
<li><p><a href="rus-create-and-update-a-facture-for-a-corrected-purchase-order.md">(RUS) Create and update a facture for a corrected purchase order</a></p></li>
<li><p><a href="rus-post-and-print-an-invoice-for-payment-for-a-free-text-invoice.md">(RUS) Post and print an invoice for payment for a free text invoice</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/hh454994(v=ax.60)">Open customer invoices (list page)</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/jj911374(v=ax.60)">(RUS) Free text invoice (modified form)</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Amount difference factures</p></td>
<td><p>An original facture must be corrected if the currency values change during the shipment of goods. After the facture is corrected, the company verifies that the sum of the correction equals the sum of the amount difference. An amount difference facture is generated when a purchase or sales transaction is settled under these conditions:</p>
<ul>
<li><p>The invoice currency and the company currency differ.</p></li>
<li><p>The payment currency is the same as the company currency.</p></li>
<li><p>The exchange rate of the invoice currency on the invoice date and the exchange rate on the payment date differ.</p></li>
<li><p>The amount difference affects the company’s VAT liability.</p></li>
</ul>
<p>An amount difference facture that is generated is processed independently of other factures, and is included in the sales and purchase books. You can print the amount difference facture and the original facture that was adjusted based on the amount difference.</p>
<p>For more information, see <a href="rus-amount-difference-factures-for-sales-and-purchase-orders.md">(RUS) Amount difference factures for sales and purchase orders</a>.</p></td>
</tr>
<tr class="even">
<td><p>Payment proposals and settlements for Russia</p></td>
<td><p>Enhancements have been made to the Accounts payable payment grouping and payments at the invoice line level.</p>
<p>In Russia, you can create a payment proposal for a vendor tax agent By using payment grouping, on the <strong>Vendor payment proposal</strong> form, you can specify the invoices that must be paid to a specific vendor, and then combine the invoices into one payment. You can periodically settle open customer transactions that include the invoices that belong to different agreement numbers.</p>
<p>You can also settle a partial payment against a particular invoice line and settle open transactions by using a periodic settlement for customers. Exchange adjustment factures are created for the settled invoice lines.</p>
<p>For more information, see <a href="rus-periodic-settlements-for-customers.md">(RUS) Periodic settlements for customers</a> and <a href="rus-create-a-payment-proposal-for-a-tax-agent-invoice.md">(RUS) Create a payment proposal for a tax agent invoice</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Allocation of miscellaneous charges</p></td>
<td><p>When you purchase a service item, you can allocate any miscellaneous charges that you incur by using a purchase order or an invoice journal. To allocate the charges, specify the miscellaneous charges code in the <strong>Item</strong> form to use a purchase order or on the invoice line to use an invoice journal.</p>
<p>There are several ways to allocate the miscellaneous charges for service items:</p>
<ul>
<li><p><strong>Include to the cost price</strong> – Include the miscellaneous charges amount in the item cost price.</p></li>
<li><p><strong>Redraw debt</strong> – Redraw the miscellaneous charges amount to third parties.</p></li>
<li><p><strong>Write-off to cost</strong> – Write off the miscellaneous charges amount to item costs.</p></li>
</ul>
<p>After you allocate the miscellaneous charges on invoices, you can view the allocation history in the <strong>Charges allocation</strong> form. You can also cancel the allocations.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj923600(v=ax.60)">(RUS) Charges allocation (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Fixed asset tax calculations and declarations</p></td>
<td><p>You can generate assessed tax, transport tax, or land tax declarations that contain information that is categorized by the Russian Federation tax authority. Tax declarations can include several territorial codes or Russian Classification of Objects of Administrative Division (RCOAD) codes for a single tax authority. An RCOAD code is a legislative or territorial code that is defined for each region or territory of the Russian Federation. In Microsoft Dynamics AX, you can set up the RCOAD codes for your company, vendors that are associated with a company division, a sales tax authority, and fixed assets, based on location.</p>
<p>When you generate fixed asset tax declarations, you can perform the following tasks:</p>
<ul>
<li><p>Specify an RCOAD code for a territory, and link the RCOAD code to a tax authority.</p></li>
<li><p>Specify an identification code for a separate company division for a fixed asset to identify the fixed asset’s division location.</p></li>
<li><p>Include the details of the division or the head office on the title page of the assessed tax and transport tax declarations.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Budget control for advance reports</p></td>
<td><p>You can use budget control to monitor budget funds, based on source documents such as purchase orders and expense reports. In the Russian Federation, advance reports are generated to register incurred expenses. You can use advance reports as source documents to check the budget and calculate expenses. You can also use advance reports to calculate the open or posted actual expenditures. These expenditures are considered when you generate budget reports.</p></td>
</tr>
<tr class="even">
<td><p>Global address book (GAB) for Russia</p></td>
<td><p>New address components, such as the street number and building number, have been added to the GAB to support the address format for Russia. You can create or modify addresses in the Russian address format. Additionally, when you create a new address record for a legal entity that is outside Russia, the address reference fields that are available automatically change, based on the address format requirements of the country where the legal entity is based.</p></td>
</tr>
<tr class="odd">
<td><p>Recover a depreciation bonus for the premature sale of a fixed asset.</p></td>
<td><p>When you sell a fixed asset before the end of the depreciation life cycle of the fixed asset, you can recover the depreciation bonus for the remainder of the life cycle. You can set up a tax register to calculate the depreciation bonus amount from the time of sale until the end of the depreciation life cycle of the fixed asset. You can then include the recovered amount in a company income account.</p></td>
</tr>
<tr class="even">
<td><p>Electronic exchange format for client bank payments</p></td>
<td><p>In the Russian Federation, client banks are used to make electronic payments, and to maintain bank account balances on behalf of a legal entity and a bank. Each bank is represented by a client bank, and different banks use different templates to transfer electronic payments. You can set up different templates to transfer the electronic payments to different banks. The client bank is used to export or import bank formats. You can now use a new electronic exchange format that supports various bank templates for electronic payments, and that provides an interface between the templates and Microsoft Dynamics AX. Additionally, you can reconcile bank account statements through the automatic reconciliation process.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to sales agreements and purchase agreements</p></td>
<td><p>Sales agreements and purchase agreements are maintained independently by selling parties and buying parties, as required by the sales and purchasing processes of each party. These agreements cover not only the products themselves, but also the agreements about the sale and purchase of products or categories of products. You can perform the following tasks by using the new purchase and sales agreement models:</p>
<ul>
<li><p>Specify contracts or agreements in general journals and transfer orders.</p></li>
<li><p>Settle customer or vendor transactions based on agreements.</p></li>
<li><p>Generate reports for sales and purchase agreements.</p></li>
<li><p>Register agreements, and include all the financial parameters.</p></li>
<li><p>Cross-check with partners by using agreements, and generate statements of reconciliation.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Credit correction for a vendor invoice and free text invoice source documents</p></td>
<td><p>You can use the credit correction parameter to post vendor invoices, purchase orders, and free text invoices for a positive amount. You can also receive messages that confirm that you are posting a positive invoice amount that has an accurate correction sign.</p></td>
</tr>
<tr class="odd">
<td><p>Facture report that is issued by tax agents</p></td>
<td><p>In accordance with federal tax service requirements, and changes in the rules for maintaining ledgers of received and issued invoices, purchases, and sales in VAT estimates, the facture printing forms that are issued by tax agents must contain specific information on the specified lines and in the specified columns of the report. The printed form of the facture contains dashes and the following information:</p>
<ul>
<li><p>The number and date of the payment order</p></li>
<li><p>The base amount without VAT</p></li>
<li><p>The computational tax rate (Computation tax rate = VAT value / VAT value + 100)</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Storno transactions in transfer journals</p></td>
<td><p>You can create and post a storno transfer journal to reverse a journal transaction that is posted incorrectly. You can also copy journals by using the Copy function to manually correct the posted quantity in the <strong>Inventory journal</strong> form. To correct an error in a storno journal after the transaction has been posted, you can create a storno-on-storno journal to reverse the storno journal transaction by using the Copy function.</p>
<p>For more information, see <a href="rus-create-and-post-a-storno-transfer-journal.md">(RUS) Create and post a storno transfer journal</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Tax rate enhancements for Russia</p></td>
<td><p>You can enter tax rates that contain five decimal places to calculate the sales tax amount. In accordance with Russian legislation, when you print the facture and invoice report, the tax rate must be included. On the report, the tax rate that is displayed includes only the significant digits.</p></td>
</tr>
<tr class="even">
<td><p>VAT deduction for deferrals</p></td>
<td><p>The VAT deduction for deferrals lets you calculate VAT refunds in proportion to the deferral amount for factures that are related to the purchase of services, operational equipment, or other commodities that are accounted as deferrals. You can use the <strong>General ledger parameters</strong> form and the <strong>Accounts payable parameters</strong> form to activate the VAT deduction for deferrals. You must select the <strong>Group by lot ID</strong> parameter in the <strong>Accounts payable parameters</strong> form. If you set the <strong>VAT offset method for deferrals</strong> parameter in the <strong>General ledger parameters</strong> form to <strong>Proportionate</strong>, the VAT refund is calculated in proportion to the deferral amount. You must also create deferrals by using the <strong>Deferrals creating</strong> form. For each deferral, you must specify the proportionate <strong>VAT offset method</strong> in the <strong>Deferrals</strong> form.</p>
<p>At the end of each tax reporting period, you must close the VAT that is received during that period by using the Incoming VAT processing process in the purchase book. When you process incoming VAT for the write-off or disposal of deferrals, you can select the factures, and verify the blocked and unblocked facture VAT amounts that are calculated. The written-off amount is unblocked and can be posted. The remaining facture amount is blocked, and its posting is postponed.</p>
<p>If you have disposed of or written off a deferral, you can reverse the transaction in the general journal to cancel the write-off or disposal if you have not yet closed the purchase book for the appropriate period.</p></td>
</tr>
<tr class="odd">
<td><p>Accounting and cost calculation of by-products and defective products</p></td>
<td><p>In accordance with Russian legislation, companies must calculate the cost of by-products and defective products that are generated during various stages of production. The by-products and defective products are registered in specific general ledger accounts. Therefore, you can determine the cost of various by-products and evaluate the reasons for reduced production of the primary product. Defective products can either be sent to inventory for rework or written off to inventory losses as scrap. You can perform the following tasks:</p>
<ul>
<li><p>Define various types of by-products and defective products.</p></li>
<li><p>Use the by-product journal to register and account for the by-products and defective products.</p></li>
<li><p>Allocate the production cost among the various by-products.</p></li>
<li><p>Calculate the cost of WIP and finished goods.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Track inventory balance turnover.</p></td>
<td><p>You can run the <strong>Inventory balance turnover</strong> report to verify the quantity, income, consumption, and stock balance in warehouses, based on dimensions such as sites, warehouses, ledger accounts, or financial dimensions. You can generate this report periodically, such as at the end of the financial period, before inventory cost recalculation, or before inventory closing. You can also generate the report by using inventory transactions that have a status of <strong>Purchased</strong>, <strong>Received</strong>, <strong>Sold</strong>, or <strong>Issued</strong>. The item total is the total amount of inventory transactions and inventory transaction adjustments for all warehouses for that item during the specified period.</p></td>
</tr>
<tr class="odd">
<td><p>Generate the <strong>VAT declaration</strong> report in .xls and .xml formats.</p></td>
<td><p>In accordance with Russian legislation, several sections on the <strong>VAT declaration</strong> report have been updated. Companies must generate the <strong>VAT declaration</strong> report in the updated format and submit the report to the sales tax authorities. The <strong>VAT declaration</strong> report can be generated in both .xls and .xml formats.</p></td>
</tr>
<tr class="even">
<td><p>Tax registration numbers are defined in a party record's address records.</p></td>
<td><p>In AX 2012 R2, tax registration numbers are no longer defined at the company level or the party record level. Instead, you can define the tax registration number on the party's primary address record.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to the land tax declaration</p></td>
<td><p>The template for the land tax declaration in Russia has changed.</p></td>
</tr>
<tr class="even">
<td><p>Changes to the transport tax declaration</p></td>
<td><p>The template for the transport tax declaration in Russia has changed.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to the property tax declaration</p></td>
<td><p>The template for the property tax declaration in Russia has changed.</p></td>
</tr>
<tr class="even">
<td><p>Changes to posting in the dual warehouse layer</p></td>
<td><p>You can perform cost value accounting by using a reporting currency. You can also perform recalculations or inventory closings, or adjust on-hand inventory or inventory receipts, in the reporting currency to generate ledger transactions. These ledger transactions use the dual warehouse posting layer. You can post purchase orders that have the inventory profile, inventory owner, and GTD inventory dimensions. You must set up a dual warehouse layer to post inventory settlements in the secondary currency. Adjustment amounts in the secondary currency are calculated based on the adjustment amount in the main currency and the exchange rates that were effective on the transaction dates.</p></td>
</tr>
<tr class="odd">
<td><p>Electronic reporting</p></td>
<td><p>For electronic reporting, you can set up financial report layouts, document templates, and fixed requisites by using the Financial reports generator.</p></td>
</tr>
<tr class="even">
<td><p>Print management for bills of lading</p></td>
<td><p>You can use print management for bills of lading and transportation documents. You can print the reports for bills of lading in Excel format and on a standard Microsoft SQL Server Reporting Services report. You can also print the transportation document, such as a job ticket or a transportation invoice, in Excel format.</p></td>
</tr>
<tr class="odd">
<td><p>Option for using the transit expense account when you post a purchase invoice</p></td>
<td><p>You can use the purchase expenditure for product account to post a purchase invoice before the document date for vendor invoices is set. This feature lets you select different dates during vendor balance posting and inventory posting.</p></td>
</tr>
<tr class="even">
<td><p>Include unpaid export factures in Russian sales books.</p></td>
<td><p>To process VAT, you can include unpaid export factures in sales books when you run processing for outgoing VAT.</p></td>
</tr>
<tr class="odd">
<td><p>Set up a default inventory profile for retail transactions in Russia.</p></td>
<td><p>You can select an inventory profile that is applied by default to sales orders that are created from transactions in Microsoft Dynamics AX for Retail POS. The default inventory profile that is assigned to the warehouse for the retail store is also used to track inventory movements when the retail statement is calculated and posted.</p></td>
</tr>
<tr class="even">
<td><p>Automatically update factures for sales invoices in Russia.</p></td>
<td><p>You can set the Retail parameters so that the facture is automatically updated when the sales invoice is posted at the same time as the retail statement.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012 R2

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
<td><p>Restore a fixed asset depreciation bonus.</p></td>
<td><p>A legal entity can restore the depreciation bonus for a fixed asset if the legal entity sells the fixed asset to an affiliated customer within five years after the fixed asset is put into operation.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-about-bonus-depreciation-for-fixed-assets-after-major-repairs.md">(RUS) About bonus depreciation for fixed assets after major repairs</a></p></li>
<li><p><a href="rus-calculate-the-depreciation-bonus-recovery-register.md">(RUS) Calculate the depreciation bonus recovery register</a></p></li>
<li><p><a href="rus-set-up-an-affiliated-customer.md">(RUS) Set up an affiliated customer</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

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
<td><p>Generate an alcohol declaration and journals</p></td>
<td><p>You can set up and generate an alcohol declaration for a quarter of a year or for a year. The declaration contains information about the sales of alcoholic items, purchases of alcoholic items, and movement of alcoholic items between separate divisions for each type of vendor, customer, or alcohol production types. You can generate a daily journal for alcohol production turnover for each division. The daily journal contains the same information about daily alcohol turnovers as in the quarterly or yearly declaration. You can generate and export an electronic reporting document for the alcohol declaration and the journal.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-parameters-for-alcohol-declarations-and-journals.md">(RUS) Set up parameters for alcohol declarations and journals</a></p></li>
<li><p><a href="rus-set-up-and-generate-an-electronic-document-for-an-alcohol-declaration.md">(RUS) Set up and generate an electronic document for an alcohol declaration</a></p></li>
<li><p><a href="rus-generate-alcohol-declarations-and-journals.md">(RUS) Generate alcohol declarations and journals</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Register retail sales by using fiscal printer integration.</p></td>
<td><p>You can register retail sales that are made at the point of sale (POS) and print fiscal receipts by using a certified Shtrih-M fiscal printer that is integrated with Retail POS. You can perform the following tasks by using fiscal printer integration:</p>
<ul>
<li><p>Configure a fiscal printer by using the POS hardware profile and the fiscal printer configuration file.</p></li>
<li><p>Configure fiscal receipt layouts, and print fiscal receipts for retail sales, returns, start amounts, float entries, tender removals, X-reports, and Z-reports.</p></li>
<li><p>Register discounted sales, sales that have multiple payments, and loyalty operations.</p></li>
<li><p>Open and close shifts at the POS and in the fiscal printer.</p></li>
<li><p>Save fiscal receipt data for the retail transactions, and transfer the data to Microsoft Dynamics AX.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-fiscal-printer-integration-for-retail-sales.md">(RUS) Fiscal printer integration for retail sales</a></p></li>
<li><p><a href="rus-configure-fiscal-printers-to-generate-a-fiscal-receipt.md">(RUS) Configure fiscal printers to generate a fiscal receipt</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Regulate the return of retail sales items at the POS.</p></td>
<td><p>You can set up parameters that determine whether the return of sales items is allowed or rejected if the return does not occur during the shift in which the items are sold. You can also set up parameters that determine whether the return of non-returnable items is allowed or rejected.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-restrictions-on-item-returns.md">(RUS) Set up restrictions on item returns</a></p></li>
<li><p><a href="rus-set-up-permission-groups-to-regulate-the-return-of-sold-items.md">(RUS) Set up permission groups to regulate the return of sold items</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Create, print, and revise factures for invoices and credit notes.</p></td>
<td><p>You can create, revise, print, and reprint a corrective facture to correct taxable transaction amounts in credit notes and invoices. When you reprint the facture, you can retain the parameters and format that were used to print the original facture without changing the tax distribution for the transactions.</p></td>
</tr>
</tbody>
</table>


## What’s new in AX 2012 R3

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
<td><p>Process gift card operations as prepayments.</p></td>
<td><p>You can set up AX 2012 R3 for Retail to process gift card operations as prepayment transactions. You can set up a default gift card customer in AX 2012 R3.</p>
<p>When you issue a gift card or add money to a gift card at the point of sale (POS), an additional value-added tax (VAT) amount is calculated for the prepayment amount that is associated with the gift card operation. The additional VAT amount is printed on the fiscal receipt. When the retail transaction data is transferred to AX 2012 R3, a prepayment is generated for each gift card operation that includes the VAT amount for the prepayment that was calculated by the fiscal printer. The liability of this prepayment transaction is associated with the default gift card customer account that you set up.</p>
<p>When you register a purchase that a customer pays for by using a gift card at the POS, the liability for the items that are paid for by using the gift card is associated with the default gift card customer. The liability is settled against the prepayment transactions that were previously registered for the same gift card.</p>
<p>Depending on the settings in the fiscal printer configuration file, a payment that is made by using a gift card can be treated as a regular payment or a cash discount on a fiscal receipt. When you register a return transaction for items that a customer paid for by using a gift card, the refund amount is added to an existing gift card, or a new gift card is issued and refunded in the same return transaction.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-parameters-to-process-gift-card-operations-as-prepayments.md">(RUS) Set up parameters to process gift card operations as prepayments</a></p></li>
<li><p><a href="rus-view-gift-card-payment-journals.md">(RUS) View gift card payment journals</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Refund payment method control in Retail POS</p></td>
<td><p>You can set up the refund payment method control in AX 2012 R3 to process refunds by using the following payment methods at the retail POS:</p>
<ul>
<li><p>The same payment method as the method that was used for the original transaction</p></li>
<li><p>A payment method other than the method that was used for the original transaction</p></li>
</ul>
<p>For more information, see <a href="rus-set-up-the-refund-payment-method-control.md">(RUS) Set up the refund payment method control</a>.</p>
<p>For more information about how to process return transactions at the POS, see “About the actions that buttons perform” and “(RUS) Perform a return transaction” in POS Help.</p></td>
</tr>
<tr class="odd">
<td><p>Process return transactions during a different shift.</p></td>
<td><p>You can set up AX 2012 R3 to process return transactions for items that are returned during a shift that differs from the shift in which the items were sold at the POS. You can use one of the following methods to process a cash return transaction during a different shift:</p>
<ul>
<li><p>Automatically create a disbursement slip for the return transaction at the POS.</p></li>
<li><p>Register a disbursement slip in AX 2012 R3 for the return transaction, and then specify the disbursement slip number during the return transaction at the POS.</p></li>
</ul>
<p>You must clear the <strong>Process as a return in the same shift</strong> check box in the <strong>Retail parameters</strong> form to process return transactions by specifying the disbursement slip number or by automatically creating a disbursement slip. When you clear this check box, no fiscal receipt is generated for the return transaction that is performed during a different shift.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-microsoft-dynamics-ax-to-process-returns-during-a-different-shift.md">(RUS) Set up Microsoft Dynamics AX to process returns during a different shift</a></p></li>
<li><p><a href="rus-verify-the-details-of-a-disbursement-slip-that-is-automatically-created-for-a-cash-return-transaction.md">(RUS) Verify the details of a disbursement slip that is automatically created for a cash return transaction</a></p></li>
<li><p><a href="rus-post-a-statement-for-return-transactions-that-are-processed-during-a-different-shift.md">(RUS) Post a statement for return transactions that are processed during a different shift</a></p></li>
</ul>
<p>For more information about how to perform a cash return transaction during a different shift at the POS, see “(RUS) Perform a cash return transaction during a different shift” in POS Help.</p></td>
</tr>
<tr class="even">
<td><p>Redeem loyalty points as discounts for sales transactions, and refund loyalty points for return transactions at the point of sale.</p></td>
<td><p>You can redeem loyalty points from a customer's loyalty card as a discount when you perform a sales transaction at the POS. You can set up AX 2012 R3 to award loyalty points for the remaining transaction amount that is paid in cash when you redeem loyalty points. You can check the point balance on a customer’s loyalty card. You can also print the point balance if a printout is required.</p>
<p>You can return an item that a customer purchased by using a loyalty points discount at the POS. You can then add the loyalty point balance either to the same loyalty card or to another loyalty card.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-microsoft-dynamics-ax-to-redeem-and-return-loyalty-points.md">(RUS) Set up Microsoft Dynamics AX to redeem and return loyalty points</a></p></li>
<li><p><a href="rus-view-the-loyalty-points-discount-amount-for-a-retail-store-transaction.md">(RUS) View the loyalty points discount amount for a retail store transaction</a></p></li>
</ul>
<p>For more information about how to redeem and return loyalty points at the POS, see “About the actions that buttons perform” and “(RUS) Perform a sales transaction to redeem loyalty points as a discount” in POS Help.</p></td>
</tr>
<tr class="odd">
<td><p>Payroll process enhancements</p></td>
<td><p>The following enhancements have been made to the payroll process:</p>
<ul>
<li><p>You can set up a payroll group for workers or employees in the <strong>Payroll groups</strong> form. You can create a payroll group of workers to define parameters that are specific to workers, such as tax residence or citizenship.</p></li>
<li><p>You can set up rates for workers and employees. Rates define the values of calculation variables, such as the rate to calculate pension fund contributions or the number of children to calculate the corresponding benefits.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-calculation-procedures-for-the-payroll-process.md">(RUS) Set up calculation procedures for the payroll process</a></p></li>
<li><p><a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a></p></li>
<li><p><a href="rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md">(RUS) Set up payments, journals, and deductions for the payroll process</a></p></li>
<li><p><a href="rus-set-up-taxes-and-funds-for-the-payroll-process.md">(RUS) Set up taxes and funds for the payroll process</a></p></li>
<li><p><a href="rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md">(RUS) Set up vacations, business trips, and incentives for the payroll process</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Payroll journal enhancements</p></td>
<td><p>The following enhancements have been made to payroll journals:</p>
<ul>
<li><p>You can select the <strong>Use rate value per employee</strong> check box for a journal name or a journal to use the date effective rate value for each employee or group that you specify in the <strong>Set up rate values</strong> form for each journal line. If you clear this check box, the default rate that you specify for the rate in the <strong>Rates</strong> form is used for all employees or groups.</p></li>
<li><p>If you select the <strong>Use rate value per employee</strong> check box for a journal, before you post the journal, you can view and modify separate lines for each employee in the group, based on the pay type that you use for the journal line.</p></li>
<li><p>You can specify the number of the incentive resolution order that is related to the payroll journal when you create the journal. The Payroll department can then create journal lines automatically, based on the lines in the incentive resolution journal that is created by the Human Resource department.</p></li>
</ul>
<p>For more information, see <a href="rus-generate-pay-statements.md">(RUS) Generate pay statements</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Settle tax liabilities.</p></td>
<td><p>You can use Microsoft Dynamics AX to match tax payments that are made to the tax authorities with tax liabilities. You can then settle the liabilities.</p>
<p>For more information, see <a href="rus-settle-tax-liabilities.md">(RUS) Settle tax liabilities</a>.</p></td>
</tr>
<tr class="even">
<td><p>Search products based on attributes at POS.</p></td>
<td><p>You can search for products based on their attributes at POS.</p></td>
</tr>
<tr class="odd">
<td><p>Manage and print product labels and shelf labels for stores.</p></td>
<td><p>You can set up Microsoft Dynamics AX to manage the price labels for products and shelves. You can print the product and shelf labels asynchronously at the retail POS. The following tasks can be performed in Microsoft Dynamics AX and at POS:</p>
<ul>
<li><p>Generate labels for products that have revised prices.</p></li>
<li><p>Generate product labels and shelf labels for received products.</p></li>
<li><p>Reprint incorrect and damaged labels.</p></li>
<li><p>Specify attributes and dimensions that should be printed on labels.</p></li>
</ul>
<p>For more information, see (RUS) Manage and print product labels or shelf labels for stores.</p></td>
</tr>
</tbody>
</table>


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
<ol>
<li><p>Setup Payment method “Cash account” for Call center.</p></li>
<li><p>Post cash payments using Slip journal in the cash management module.</p></li>
</ol>
<p>You can perform the following tasks for prepayments:</p>
<ol>
<li><p>Create and post prepayments (include sales tax on prepayment) using special setup for Russia and Eastern Europe countries.</p></li>
</ol>
<p>You can peform the following tasks for gift cards:</p>
<ol>
<li><p>Gift card issue with RU requirements for accounting</p></li>
<li><p>Gift card replenishment with RU requirements for accounting</p></li>
<li><p>Payment with gift cards</p></li>
<li><p>Refund to Gift card</p></li>
<li><p>Void operation for Gift card</p></li>
<li><p>Support Gift card policies</p></li>
</ol></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 9

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
<td><p>Updates to VAT deduction acceptance</p></td>
<td><p>Updates have been made to the VAT deduction acceptance that now allow the following:</p>
<ul>
<li><p>Accept VAT deduction in the period of the document’s receipt or in the current reporting period if the facture is received before the VAT declaration submission date.</p></li>
<li><p>Include only the commissioners’ factures in the Facture journal according to the requirements of the Judgment N 735 from July 30, 2014 from the RF government.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Journal of alcohol products</p></td>
<td><p>The journal format used in accounting of the retail sale of alcoholic products has been updated based on the changes enacted on May 23, 2014 N 153 from the Federal Service for Alcohol Market Regulation. The journal format now shows incoming and outgoing documents instead of grouping the documents. The following has also been added to the journal:</p>
<ul>
<li><p>Packing volume in liters and the number of packages.</p></li>
<li><p>Description from transfer type or scrap type.</p></li>
<li><p>Sell products.</p></li>
<li><p>Product loss during transport, fight products, and other losses.</p></li>
<li><p>Production loss identified in inventory.</p></li>
<li><p>Arrested products.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Transport tax declaration</p></td>
<td><p>The Transport tax declaration electronic format has been updated according to Federal tax authority order N ММВ-7-11/254@ from April 25, 2014.</p></td>
</tr>
<tr class="even">
<td><p>Reports</p></td>
<td><p>The printable format of the 4-FSS report has changed effective Q1 2015. You can now generate the report according to the new printable format.</p>
<p>A new format of the Form No. 1 statistical report is now available.</p></td>
</tr>
<tr class="odd">
<td><p>Tax agent facture numbers</p></td>
<td><p>The facture that is created for the tax agent can have the same number in the purchase book and the sales book because there are two copies of one document.</p></td>
</tr>
<tr class="even">
<td><p>Facture registration journals</p></td>
<td><p>When you create Facture registration journals, you can now create journals according to the date of registration of the outgoing facture or according to the date of registration of the confirming incoming facture.</p></td>
</tr>
<tr class="odd">
<td><p>VAT declaration</p></td>
<td><p>The VAT declaration electronic format has been updated to version 5.04.</p></td>
</tr>
<tr class="even">
<td><p>Customer order scenarios and integration with fiscal printers</p></td>
<td><p>Customer payments that are registered in Retail Enterprise POS for customer order deposits and partially completed orders can now be reflected in fiscal receipts.</p></td>
</tr>
<tr class="odd">
<td><p>Cancel amount differences in tax accounting</p></td>
<td><ul>
<li><p>The tax registers, <strong>Amount difference in tax accounting</strong> and <strong>Exchange adjustment in accounting</strong>, show only the amount of the exchange differences from invoices that were posted before January 1, 2015.</p></li>
<li><p>The currency exchange differences for invoices that were created after January 1, 2015, either as a result of a periodic exchange adjustment calculation or a settlement, are reflected in the tax registers that collect transactions by the general ledger accounts.</p></li>
<li><p>To identify currency exchange differences in general ledger accounts for tax purposes, the dimension <strong>Expense code</strong> is filled with values that were set up to show exchange differences in the <strong>Exchange rates</strong> form (version 5.0 SP1), or in the <strong>Currency parameters</strong> form (version 6.2 and higher). This is the result of periodic currency exchange differences calculated in the accounts receivable and accounts payable modules.</p></li>
<li><p>The option to exclude is now available in the <strong>Amount difference in tax accounting</strong> and <strong>Exchange adjustment in accounting</strong> tax registers. If this check box is selected, the register will not be initiated in new tax register journals.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Registering and using the credit institutions of workers</p></td>
<td><p>The procedure for registering and using the requisites of credit institutions of workers has changed. The new 333-FZ introduced changes in the Labor Code of the Russian Federation which allows changes to the requisites of an employee’s credit institution based on their written request to the employer. These changes are applied no later than five working days before the date of payment of wages.</p></td>
</tr>
</tbody>
</table>

  


