---
title: "What's new: Country-specific features for Japan (JPN)"
TOCTitle: Country-specific features for Japan
ms:assetid: 796b30fa-7878-4365-b12f-2156067a1f6a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527147(v=AX.60)
ms:contentKeyID: 59623276
ms.date: 11/14/2014
mtps_version: v=AX.60
---

# What's new: Country-specific features for Japan (JPN) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012, we changed and added country-specific functionality for Japan. This topic is divided into two sections. The first section outlines the key features that have a broad impact on Japanese installations, such as features that affect consolidated invoices, cash flow statements, bills of exchange, financial dimensions, and the global address book (GAB). The second section describes additional changes to country-specific functionality for Japan. For more information about specific features for Japan, see [TechNet Library for Application Users - Japan](http://go.microsoft.com/fwlink/?linkid=299914).

## Key features for Japan in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3

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

AX 2012 R2 and AX 2012 R3 includes new functionality for consolidating invoices, generating cash flow statements, generating bills of exchange, and creating financial dimensions.

## Comparison with Microsoft Dynamics AX 2009

These features have changed considerably since AX 2009. AX 2012 R2 and AX 2012 R3 includes changes to the following areas:

  - Consolidated invoices

  - Cash flow statements

  - Bills of exchange

  - Financial dimensions

  - Global address book

## Consolidated invoices

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
<td><p>Consolidate monthly invoices.</p></td>
<td><p>Not available</p></td>
<td><p>You can combine multiple posted invoices from purchase orders or sales orders, purchase journals or customer journals, and purchase return orders or sales return orders. After you create consolidated invoices for a vendor or a customer, you can pay the vendor or receive a payment from the customer every month.</p></td>
<td><ul>
<li><p>Consolidated invoicing might reduce the time, the amount of paper, and the cost that are required for daily invoicing.</p></li>
<li><p>Consolidated invoicing might reduce the time that is required for cash posting.</p></li>
<li><p>Consolidated invoicing might reduce the number of invoices that have to be processed for your vendors and customers.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Calculate a due date for a payment, based on the cutoff date.</p></td>
<td><p>Not available</p></td>
<td><p>You can calculate the due date for a vendor or customer payment, based on the cutoff date.</p>
<p>The summary calculation for consolidated customer invoices is updated.</p></td>
<td><p>You have flexibility, so that you can select the appropriate consolidation date for your organization.</p></td>
</tr>
<tr class="odd">
<td><p>Consolidate customer invoices.</p></td>
<td><p>Not available</p></td>
<td><p>You can now set the status of consolidated invoices as follows:</p>
<ul>
<li><p><strong>Unconfirmed</strong></p></li>
<li><p><strong>Confirmed</strong></p></li>
<li><p><strong>Settled</strong> and <strong>Partially settled</strong></p></li>
</ul></td>
<td><p>You can manage more complex scenarios for invoice consolidation.</p></td>
</tr>
<tr class="even">
<td><p>Reopen consolidated vendor invoices.</p></td>
<td><p>Not available</p></td>
<td><p>You can reopen a consolidated vendor invoice.</p></td>
<td><p>You can make corrections to vendor invoices.</p></td>
</tr>
<tr class="odd">
<td><p>Include partially settled invoices in a consolidated invoice.</p></td>
<td><p>Not available</p></td>
<td><p>When you create a consolidated vendor invoice, you can include amounts from partially settled invoices. Settlement might include letters of credit.</p></td>
<td><ul>
<li><p>Consolidated invoicing might reduce the time, the amount of paper, and the cost that are required for daily invoicing.</p></li>
<li><p>Consolidated invoicing might reduce the time that is required for cash posting.</p></li>
<li><p>Consolidated invoicing might reduce the number of invoices that have to be processed for your vendors and customers.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Consolidate invoices based on the execution date instead of the consolidation date.</p></td>
<td><p>Not available</p></td>
<td><p>You can consolidate Accounts receivable (AR) invoices based on the execution date instead of the consolidation date. You can also consolidate Accounts payable (AP) invoices based on the execution date instead of the consolidation date.</p></td>
<td><p>You have flexibility when you determine the consolidation date for a consolidated invoice.</p></td>
</tr>
<tr class="odd">
<td><p>Define consolidation dates for your customers.</p></td>
<td><p>Not available</p></td>
<td><p>You can define a consolidation date for each customer.</p></td>
<td><p>The default consolidation date is set automatically when you create a consolidated customer invoice.</p></td>
</tr>
<tr class="even">
<td><p>Consolidate vendor invoices for payment proposals.</p></td>
<td><p>Not available</p></td>
<td><p>You can create consolidated invoices for payment proposals for vendors.</p></td>
<td><p>The consolidation of vendor invoices, payment proposals, and so on is simplified.</p></td>
</tr>
<tr class="odd">
<td><p>Add non-purchase order lines to a consolidated invoice.</p></td>
<td><p>Not available</p></td>
<td><p>When you create a consolidated invoice, you can include both invoice lines that are related to a purchase order and free-text invoice lines that are not related to a purchase order.</p></td>
<td><p>You can include free-text invoice lines in a consolidated invoice.</p></td>
</tr>
<tr class="even">
<td><p>Set a parameter to enable consolidation of invoices for Japan.</p></td>
<td><p>Not available</p></td>
<td><p>You can set a parameter to enable consolidation of invoices by customer. You can also set a parameter to enable consolidation of invoices by vendor.</p></td>
<td><p>The setup of consolidated invoices is simplified.</p></td>
</tr>
</tbody>
</table>


## Cash flow statements

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
<td><p>Generate cash flow statements by financial dimensions. Endorse a bill of exchange.</p></td>
<td><p>Not available</p></td>
<td><p>You can generate a cash flow statement for a financial dimension that you specify. You can also export cash flow statements to Microsoft Excel.</p></td>
<td><p>It is easier to prepare the cash flow statement for your organization and its financial dimensions.</p></td>
</tr>
</tbody>
</table>


## Bills of exchange

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
<td><p>Endorse a bill of exchange.</p></td>
<td><p>Not available</p></td>
<td><p>You can endorse a bill of exchange by settling the bill of exchange and setting the status to <strong>Drawn</strong>. You can then redraw the bill of exchange and generate the endorsement accounting journal voucher.</p></td>
<td><p>It is easier to endorse of a bill of exchange.</p></td>
</tr>
</tbody>
</table>


## Financial dimensions

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
<td><p>Define financial dimensions for debits and credits.</p></td>
<td><p>Not available</p></td>
<td><p>You can define financial dimensions for debits and credits separately. The debit and credit amounts can be entered as two lines in the journal voucher.</p></td>
<td><p>Reporting by financial dimension is simplified.</p></td>
</tr>
</tbody>
</table>


## Global address book

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
<td><p>Set up phonetic names for your companies, customers, vendors, employees, and contact persons.</p></td>
<td><p>Not available</p></td>
<td><p>You can set up phonetic names for your companies, customers, vendors, employees, and contact persons in the GAB.</p>
<p>You can also import the Japanese ZIP Codes or postal codes that are published by the Japan Postal Office in the required format.</p></td>
<td><p>This feature helps guarantee that the names of your companies, customers, vendors, employees, and contact persons are pronounced correctly.</p></td>
</tr>
</tbody>
</table>


## Additional features

For more information about additional country-specific features that we added for Japan, see the tables that apply to your version of the product.

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
<td><p>Monthly consolidated invoices</p></td>
<td><p>According to the Accounting Standards Board of Japan (ASBJ), consolidating monthly invoices for payment is a common business practice in Japan. You can combine multiple posted invoices from purchase orders or sales orders, purchase journals or customer journals, and purchase return orders or sales return orders. After you create consolidated invoices for vendors or customers, you can pay the vendors or receive payment from the customers every month.</p>
<p>You can calculate the due date for a vendor or customer payment, based on the cutoff day.</p>
<p>The following changes have been made to the consolidation process:</p>
<ul>
<li><p>The <strong>Unconfirmed</strong>, <strong>Confirmed</strong>, <strong>Settled</strong>, and <strong>Partially settled</strong> statuses have been added for consolidated customer invoices. Additionally, you can reopen a consolidated customer invoice.</p></li>
<li><p>The <strong>Partially settled</strong> status has been added for consolidated vendor invoices, so that you can partially settle consolidated vendor invoices.</p></li>
<li><p>AR and AP invoices can be consolidated based on the <strong>Execution date</strong> field instead of the consolidation date.</p></li>
<li><p>You can select an invoice for consolidation by using the consolidation date that is defined in the <strong>Customers</strong> form.</p></li>
<li><p>You can select an order to invoice based on the consolidation date in the sales update.</p></li>
<li><p>You can create consolidated invoices for payment proposals.</p></li>
<li><p>The summary calculation for consolidated customer invoices has been updated.</p></li>
</ul>
<p>For more information, see <a href="jpn-create-confirm-reopen-and-print-a-consolidated-customer-invoice.md">(JPN) Create, confirm, reopen, and print a consolidated customer invoice</a> and <a href="jpn-create-confirm-reopen-and-print-a-consolidated-vendor-invoice.md">(JPN) Create, confirm, reopen, and print a consolidated vendor invoice</a>.</p></td>
</tr>
<tr class="even">
<td><p>Cash flow statements for Japan</p></td>
<td><p>Cash flow statements display the cash inflow and outflow from the economic activities of a company for a financial period. The cash flow statements provide the following information:</p>
<ul>
<li><p>The cash flow information. This information includes the cash inflow and outflow for economic activities such as tax refunds, absorption of investment, and the cash amounts at the beginning and end of the financial period.</p></li>
<li><p>The cash changes at the beginning and end of the financial period.</p></li>
<li><p>You can also plan the cash flow statements for the next financial period. The detailed cash flow information contains economic activities such as sales order transactions, production manufacturing, fixed assets investments, and common stock cash dividends. The economic activities are then posted in the related ledger accounts. This cash flow statement generates the required information from the dimensions table, the ledger table, ledger transactions, and the cash flow that is calculated from the amount of the transactions.</p></li>
</ul>
<p>The cash flow statement is generated in an Excel worksheet.</p>
<p>For more information, see <a href="jpn-set-up-and-generate-a-cash-flow-statement.md">(JPN) Set up and generate a cash flow statement</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Phonetic field names in the GAB for Japan</p></td>
<td><p>You can set up the phonetic names for your companies, customers, vendors, employees, and contact persons in the GAB. Phonetic names guarantee that the names of your companies, customers, vendors, employees, and contact persons are pronounced correctly.</p>
<p>You can also import the Japanese ZIP Codes or postal codes that are published by the Japan Postal Office in the required format.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/jj711047(v=ax.60)">(JPN) Global address books and address reference data</a> and <a href="jpn-import-japanese-zip-postal-codes.md">(JPN) Import Japanese ZIP/postal codes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Consolidated invoices and letters of credit</p></td>
<td><p>You can include a letter of credit when you create a consolidated invoice. This feature is available only for Japan.</p>
<p>For more information, see <a href="jpn-create-confirm-reopen-and-print-a-consolidated-customer-invoice.md">(JPN) Create, confirm, reopen, and print a consolidated customer invoice</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Endorse a bill of exchange.</p></td>
<td><p>You can endorse a bill of exchange in Microsoft Dynamics AX by settling the bill of exchange and setting the status to <strong>Drawn</strong>. You can then redraw the bill of exchange and generate the endorsement accounting journal entry.</p>
<p>For more information, see <a href="jpn-create-and-endorse-a-bill-of-exchange.md">(JPN) Create and endorse a bill of exchange</a>.</p></td>
</tr>
<tr class="even">
<td><p>Financial dimension attributes for Japan</p></td>
<td><p>You can define several financial dimension attributes, in addition to the department, cost center, and purpose, so that you can view and modify account and journal information.</p>
<p>The debit and credit amounts can be entered as two lines in the T-account journal voucher.</p>
<p>For more information, see <a href="jpn-set-up-a-t-account-journal-and-t-accounts.md">(JPN) Set up a T-account journal and T-accounts</a>. For more information about financial dimensions, see <a href="what-s-new-financial-dimensions-framework.md">What's new: Financial dimensions framework</a> and <a href="http://go.microsoft.com/fwlink/?linkid=213133%26clcid=0x409">Implementing the Account and Financial Dimensions Framework for Microsoft Dynamics AX 2012 Applications</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Generate financial statements in Excel for Japan.</p></td>
<td><p>You can export financial statements, such as balance sheets, profit and loss statements, and cash flow statements, to Excel.</p>
<p>For more information, see <a href="jpn-print-a-japanese-financial-statement.md">(JPN) Print a Japanese financial statement</a>.</p></td>
</tr>
<tr class="even">
<td><p>Invoice lines in a consolidated invoice</p></td>
<td><p>The consolidated invoice can include both invoice lines that are related to a purchase order and invoice lines that are not related to a purchase order.</p>
<p>For more information, see <a href="jpn-about-consolidating-invoices.md">(JPN) About consolidating invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Target of consolidation</p></td>
<td><p>The <strong>Target of consolidation</strong> check box is available on the <strong>Sales order</strong>, <strong>Purchase order</strong>, and <strong>Vendor invoice</strong> forms. When selected, it indicates that the transaction will be invoiced using invoice consolidation.</p></td>
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
<td><p>Debit and credit amounts in the transaction currency</p></td>
<td><p>You can configure Microsoft Dynamics AX to add the <strong>Debit amount in transaction currency</strong> and <strong>Credit amount in transaction currency</strong> fields to the <strong>Customer transactions</strong> form and the <strong>Vendor transactions</strong> form.</p>
<p>For more information, see <a href="jpn-set-up-the-parameter-to-add-debit-and-credit-fields-in-the-vendor-transactions-form.md">(JPN) Set up the parameter to add debit and credit fields in the Vendor transactions form</a> and <a href="jpn-set-up-the-parameter-to-add-debit-and-credit-fields-in-the-customer-transactions-form.md">(JPN) Set up the parameter to add debit and credit fields in the Customer transactions form</a>.</p></td>
</tr>
<tr class="even">
<td><p>Calculate payment fees.</p></td>
<td><p>When a legal entity makes a payment to a vendor, the bank payment fees can be paid by the legal entity or the vendor.</p>
<p>When the vendor pays the bank payment fees, you can perform the following tasks:</p>
<ul>
<li><p>Specify whether the vendor pays the bank payment fees.</p></li>
<li><p>Create a bank rule for the payment fee.</p></li>
<li><p>Set up a payment fee.</p></li>
<li><p>Create and post a payment journal, so that the payment fee is automatically calculated by using the bank rule.</p></li>
<li><p>Generate the payment file.</p></li>
</ul>
<p>For more information, see <a href="jpn-set-up-and-calculate-the-bank-payment-fees-for-a-vendor.md">(JPN) Set up and calculate the bank payment fees for a vendor</a> and <a href="jpn-bank-payment-fees-for-vendors.md">(JPN) Bank payment fees for vendors</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Allocate the cost of fixed asset depreciation to multiple organization units, and track the history of location transfers.</p></td>
<td><p>You can set up allocation rules to allocate and share the depreciation costs of fixed assets among organization units that have used the asset. You can also track the movement of an asset to a new location.</p>
<p>For more information, see <a href="chn-jpn-create-allocation-rules-and-allocate-depreciation-costs.md">(CHN, JPN) Create allocation rules and allocate depreciation costs</a> and <a href="chn-jpn-allocation-rules-for-fixed-assets.md">(CHN, JPN) Allocation rules for fixed assets</a>.</p></td>
</tr>
<tr class="even">
<td><p>Calculate depreciation for fixed assets.</p></td>
<td><p>You can use Microsoft Dynamics AX to calculate the depreciation and depreciation expenses for tangible and intangible fixed assets by using the following depreciation methods:</p>
<ul>
<li><p>Old straight line method</p></li>
<li><p>New straight line method</p></li>
<li><p>Old declining balance method</p></li>
<li><p>200 percent declining balance method</p></li>
<li><p>250 percent declining balance method</p></li>
</ul>
<p>You can specify the allowable limit for accumulated depreciation, or the maximum amount of a depreciation expense that can be deducted from the acquisition value of a fixed asset for a specific period. The allowable limit depends on the depreciation method that you apply to the fixed asset, and whether the fixed asset is tangible or intangible. You can calculate depreciation annually or monthly. A catch-up rule can be used to adjust depreciation amounts for monthly depreciation.</p>
<p>You can use Microsoft Dynamics AX to perform the following tasks when you depreciate a fixed asset:</p>
<ul>
<li><p>Calculate depreciation by using a depreciation method.</p></li>
<li><p>Change the depreciation method for a fixed asset after the fixed asset was depreciated by using other methods in previous periods.</p></li>
<li><p>Calculate depreciation for a fixed asset for a fiscal year that has less than 12 months.</p></li>
</ul>
<p>For more information, see <a href="jpn-set-up-depreciation-and-depreciation-methods.md">(JPN) Set up depreciation and depreciation methods</a>.</p></td>
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
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Apply asset retirement obligation (ARO) to calculate interest expenses, depreciation amounts, and retirement costs.</p></td>
<td><p>You can use Microsoft Dynamics AX to apply ARO to a tangible fixed asset when you acquire or construct the asset. ARO is used to estimate the costs that are related to the future disposal of an asset.</p>
<p>You can perform the following tasks by using ARO:</p>
<ul>
<li><p>Specify the ARO type to use for the asset, and also specify the frequency at which the changes to the ARO amounts are posted.</p></li>
<li><p>Set up a discount rate schedule that uses current market discount rates to calculate the current value of the ARO.</p></li>
<li><p>Set up an estimated retirement cost plan for the ARO, and simulate ARO amounts for each fiscal period.</p></li>
<li><p>Adjust ARO amounts up or down to calculate interest expenses if the estimated retirement cost for the fixed asset changes.</p></li>
</ul>
<p>You can then apply the ARO amounts when you depreciate or amortize the fixed asset.</p>
<p>For more information, see <a href="jpn-set-up-asset-retirement-obligation-for-fixed-assets.md">(JPN) Set up asset retirement obligation for fixed assets</a>, <a href="jpn-asset-retirement-obligation-for-fixed-assets.md">(JPN) Asset retirement obligation for fixed assets</a>, and <a href="jpn-depreciate-and-retire-a-fixed-asset-with-asset-retirement-obligation.md">(JPN) Depreciate and retire a fixed asset with asset retirement obligation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Calculate fixed asset impairments.</p></td>
<td><p>You can perform the following tasks to set up and calculate fixed asset impairments by using Microsoft Dynamics AX:</p>
<ul>
<li><p>Generate a list of fixed assets that might be impaired. You can then manually review and calculate the undiscounted cash flow, fair value, or recoverable amounts of each asset in the list to determine the impaired fixed assets.</p></li>
<li><p>Update impairment indicators, such as undiscounted cash flow or the recoverable amount of the fixed assets. The impairment indicators are used to determine the extent of impairment for a fixed asset.</p></li>
<li><p>Run the impairment recognition test to generate the list of impaired fixed assets. You can then create journal transactions for these impaired fixed assets. You can specify the details about the impairment before you post the journal.</p></li>
<li><p>Reverse impairment losses, but only if you select <strong>IFRS</strong> (International Financial Reporting Standards) in the <strong>Accounting standard</strong> field in the <strong>Fixed assets parameters</strong> form.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="jpn-set-up-impairment-accounting-for-fixed-assets.md">(JPN) Set up impairment accounting for fixed assets</a></p></li>
<li><p><a href="jpn-identify-impaired-assets-and-post-journals-for-impairment.md">(JPN) Identify impaired assets and post journals for impairment</a></p></li>
<li><p><a href="jpn-impairment-accounting-for-fixed-assets.md">(JPN) Impairment accounting for fixed assets</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Fixed asset reports for Japan</p></td>
<td><p>You can manually generate the following reports for fixed assets by using Microsoft Dynamics AX:</p>
<ul>
<li><p><strong>Corporation Tax Act. Appended Table No.16(1)</strong> – This report contains information about the amortization calculation of depreciable assets that uses the new straight line method or the old straight line method.</p></li>
<li><p><strong>Corporation Tax Act. Appended Table No.16(2)</strong> – This report contains information about the amortization calculation of depreciable assets that uses the 200 percent or 250 percent declining balance method, or the old declining balance method.</p></li>
<li><p><strong>Form 26 - Depreciable assets tax</strong> – This report contains details about all the transactions for depreciable fixed assets.</p></li>
<li><p><strong>Form 26 - Depreciable assets tax - Appended table 1</strong> – This report contains details about the transactions that increase the value of depreciable fixed assets. These transactions can be acquisitions, acquisition adjustments, revaluations that increase the value of fixed assets, or write-up adjustments.</p></li>
<li><p><strong>Form 26 - Depreciable assets tax - Appended table 2</strong> – This report contains details about the transactions that decrease the value of depreciable fixed assets. These transactions can be fixed asset disposals, revaluations that decrease the value of fixed assets, or write-down adjustments.</p></li>
</ul>
<p>For more information, see <a href="jpn-generate-fixed-assets-reports.md">(JPN) Generate Fixed assets reports</a>.</p></td>
</tr>
<tr class="even">
<td><p>Reduction entry subsidy for Japan</p></td>
<td><p>When you acquire a fixed asset by using a government subsidy, the subsidy is treated as taxable revenue. You can use the following reduction entry methods to record the government subsidy for a fixed asset acquisition:</p>
<ul>
<li><p><strong>Direct-off method</strong> – The amount of the government subsidy is deducted directly from the acquisition cost of the fixed asset.</p></li>
<li><p><strong>Reserve method</strong> – The amount of the government subsidy is maintained as a separate value on the equity side of the balance sheet. The amount of the government subsidy does not affect the net book value of the fixed asset.</p></li>
</ul>
<p>You can perform the following tasks to record a government subsidy for a fixed asset acquisition:</p>
<ul>
<li><p>Set up a reduction entry document that is used to identify the fixed assets that are eligible for subsidy.</p></li>
<li><p>Assign a reduction entry document to a fixed asset. Alternatively, you can assign reduction entry documents to multiple fixed assets.</p></li>
<li><p>Set up a fixed asset posting profile for a reduction entry.</p></li>
<li><p>Create and post a fixed asset journal by specifying the reduction entry details.</p></li>
<li><p>Create and post a purchase order to use the subsidy for additional fixed asset acquisitions.</p></li>
<li><p>When you run a depreciation proposal, Microsoft Dynamics AX automatically calculates and posts the allocation of reduction entry together with the depreciation process.</p></li>
<li><p>Set up and run a batch process to periodically update the reduction entry documents. In the setup of the batch process, you specify criteria such as fixed asset groups and periods.</p></li>
<li><p>If you must perform this task to claim a government grant, generate a reduction entry proposal for fixed assets by attaching the reduction entry document to the proposal.</p></li>
</ul>
<p>If you calculate depreciation for a fixed asset that you acquire by using the subsidy, Microsoft Dynamics AX adjusts the calculations for depreciation and threshold, depending on the subsidy for the fixed asset.</p>
<p>You can generate the <strong>Reduction entry transaction summary</strong> report. This report contains details about the reduction entry transactions, based on criteria that you specify, such as the fiscal year, reduction entry method, and book type.</p>
<p>For more information, see <a href="jpn-set-up-reduction-entry-for-fixed-assets.md">(JPN) Set up reduction entry for fixed assets</a>, <a href="jpn-apply-reduction-entry-and-depreciate-fixed-assets.md">(JPN) Apply reduction entry and depreciate fixed assets</a>, and <a href="jpn-reduction-entry-for-fixed-assets.md">(JPN) Reduction entry for fixed assets</a>.</p></td>
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
<td><p>Assemble or disassemble fixed assets by using on-hand inventory items.</p></td>
<td><p>You can set up AX 2012 R3 to enable the assembly or disassembly of a fixed asset by using on-hand inventory items. You can perform the following tasks:</p>
<ul>
<li><p><strong>Assemble a fixed asset by using on-hand inventory items</strong> – You can reserve the list of assembly components for a fixed asset. You can then create and post an acquisition journal or an acquisition adjustment journal for the fixed asset by deducting the on-hand inventory items. The difference between the acquisition cost and the inventory cost is posted to the acquisition offset account that you specify in the fixed assets posting profile.</p></li>
<li><p><strong>Disassemble inventory items during fixed asset maintenance or after fixed asset disposal</strong> – You can reserve the list of disassembled components that can be included in inventory and reused after the fixed asset is maintained or disposed of. You can then create and post a write-down regulation journal or a disposal scrap journal to disassemble the fixed asset and include the components in inventory for reuse.</p></li>
</ul>
<p>For more information, see <a href="jpn-set-up-and-use-microsoft-dynamics-ax-to-assemble-or-disassemble-fixed-assets.md">(JPN) Set up and use Microsoft Dynamics AX to assemble or disassemble fixed assets</a>.</p></td>
</tr>
<tr class="even">
<td><p>Fixed asset reports for deferred, low-value, and lump-sum fixed assets</p></td>
<td><p>You can generate the following annual reports for fixed assets by using AX 2012 R3:</p>
<ul>
<li><p><strong>National Tax Act. Appended Table No.16 (6)</strong> – This report contains information about the amortization of deferred assets that is calculated by using either the equally divided depreciation method or depreciation amounts that are manually specified for each fiscal period.</p></li>
<li><p><strong>National Tax Act. Appended Table No.16 (7)</strong> – This report contains information about the amortization of low-value assets that is calculated by using either the equally divided depreciation method or depreciation amounts that are manually specified for each fiscal period.</p></li>
<li><p><strong>National Tax Act. Appended Table No.16 (8)</strong> – This report contains information about the amortization of lump-sum value assets that is calculated by using either the equally divided depreciation method or depreciation amounts that are manually specified for each fiscal period.</p></li>
</ul>
<p>For more information, see <a href="jpn-generate-fixed-assets-reports.md">(JPN) Generate Fixed assets reports</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Categorize and depreciate deferred, low-value, or lump-sum fixed assets.</p></td>
<td><p>You can use the <strong>Fixed asset</strong> form to categorize a fixed asset as a deferred, low-value, or lump–sum asset. You can perform the following tasks:</p>
<ul>
<li><p>Set up a fixed asset as a deferred fixed asset, and then set up one of the following depreciation techniques for the fixed asset:</p>
<ul>
<li><p><strong>Equally divided</strong> – The depreciation amount is equally divided among all the fiscal periods in the useful life of the fixed asset.</p></li>
<li><p><strong>One time</strong> – You can manually set up a depreciation amount for each fiscal period.</p></li>
</ul></li>
<li><p>Categorize a <strong>Tangible</strong>, <strong>Intangible</strong>, <strong>Financial</strong>, <strong>Land and buildings</strong>, <strong>Goodwill</strong>, or <strong>Other</strong> fixed asset as a low-value or lump-sum fixed asset, depending on the acquisition value of the fixed asset.</p></li>
</ul>
<p>You can then set up the <strong>Equally divided</strong> depreciation method in the <strong>Depreciation profiles</strong> form to depreciate the deferred, low-value, or lump-sum fixed assets over one or more fiscal periods.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="jpn-set-up-depreciation-and-depreciation-methods.md">(JPN) Set up depreciation and depreciation methods</a></p></li>
<li><p><a href="jpn-categorize-a-fixed-asset-as-a-deferred-low-value-or-lump-sum-fixed-asset.md">(JPN) Categorize a fixed asset as a deferred, low value, or lump sum fixed asset</a></p></li>
<li><p><a href="jpn-equally-divided-depreciation-method.md">(JPN) Equally divided depreciation method</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 8 for AX 2012 R3.

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
<td><p>Calculation algorithm for asset retirement</p></td>
<td><p>The calculation algorithm for asset retirement obligation (ARO) is changed to amortize ARO to the ratio, where the accumulated amortization of ARO is equal to the accumulated depreciation of the underlying fixed asset.</p></td>
</tr>
<tr class="even">
<td><p>Practical improvements on Japanese ordinary depreciation methods</p></td>
<td><p>You can choose to spread the depreciation amount in the last 5 years for Old-straight-line and Old-declining-balance methods. Also, the Net book value as of the depreciation method change timing is displayed.</p></td>
</tr>
<tr class="odd">
<td><p>Electronic declaration method to calculate the depreciable asset tax</p></td>
<td><p>A new depreciation method, electronic declaration is introduced to calculate the depreciation amount for the specific method. Related functionalities such as depreciation rate schedule, value model, form 26 report and its appended tables reports are also updated accordingly.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

