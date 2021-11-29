---
title: "What's new: Country-specific features for China (CHN)"
TOCTitle: Country-specific features for China
ms:assetid: 3bf77a0d-698d-4bcc-af87-335fce37d147
ms:mtpsurl: https://technet.microsoft.com/library/Dn507105(v=AX.60)
ms:contentKeyID: 59623195
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
---

# What's new: Country-specific features for China (CHN) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we changed and added country-specific functionality for China. This topic is divided into two sections. The first section outlines the key features that have a broad impact on Chinese installations, such as features that affect General ledger, tax integration with the Chinese Golden Tax System (GTS), Inventory and product management, and reporting. The second section describes additional changes to country-specific functionality for China. For more information about specific features for China, see [TechNet Library for Application Users - China](https://go.microsoft.com/fwlink/?linkid=299906).

## Key features for China

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

The following features were added to comply with Chinese accounting and regulatory requirements:

  - Define a hierarchical structure for a chart of accounts.

  - Use financial dimensions to allocate and post transactions to ledger accounts, bank reconciliation journals, and the Chinese voucher system.

  - Voucher types and Chinese voucher numbers are implemented in source documents, reports, and queries.

  - Subledger journal entries are created for most transactions. Use the subledger journal to view a summary of transaction amounts before the transaction is posted to the general ledger.

  - Inventory reports provide details about inventory transactions and balances.

  - Define parameters and XML files for the GB/T 24589-2010 report.

## Comparison with Microsoft Dynamics AX 2009

These features have changed considerably since AX 2009. Microsoft Dynamics AX 2012 includes changes to the following areas:

  - General ledger

  - Tax integration with the Chinese Golden Tax System

  - Inventory and product management

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
<th><p>AX 2012 R2</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View, modify, and print transactions on subledger journal lines before you post the transactions to the general ledger. Allocate transaction lines among multiple financial dimensions.</p></td>
<td><p>Not available</p></td>
<td><p>You can generate subledger journals from source documents such as invoices, packing slips, and picking lists for customers and vendors. Before you post the transaction amounts to the general ledger, you can view and modify subledger journals by using a new method that is named distribution. This method lets you allocate posting amounts among multiple financial dimensions. This method also lets you change the default ledger account number or financial dimension values, based on user permissions.</p></td>
<td><p>You can verify information before it is posted.</p></td>
</tr>
<tr class="even">
<td><p>Assign, view, and print Chinese voucher types and voucher numbers on documents.</p></td>
<td><p>The Chinese voucher type and Chinese voucher number were implemented in the ledger entries. By default, voucher numbers were assigned in a continuous sequence. Chinese voucher types and voucher numbers were available in filters for ledger entry queries.</p></td>
<td><p>You can enter transactions by using a new Chinese voucher form. You can review and correct gaps in a voucher number sequence at the end of a fiscal period by using new features in existing reports and 11 new financial reports. You can also print ledger vouchers that have Chinese voucher numbers, and print financial reports that have Chinese voucher types and voucher numbers.</p></td>
<td><ul>
<li><p>This feature complies with Chinese posting requirements for vouchers.</p></li>
<li><p>Tracking of voucher number sequences is simplified.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Set up ledger accounts to manage multiple inventory locations.</p></td>
<td><p>Not available</p></td>
<td><p>Set up multiple sites and inventory locations. You can set up or modify item postings to various ledger accounts for different sites, and you can indicate each inventory item group. You can also activate combinations of inventory transactions for sites, and then post the site details in the sales orders, purchase orders, inventory journals, or production journals. You can view the ledger accounts by the inventory value of each site in the <strong>Chart of accounts</strong> form.</p></td>
<td><p>You have more flexibility when you manage inventory for multiple sites.</p></td>
</tr>
</tbody>
</table>


## Tax integration with the Chinese Golden Tax System

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
<th><p>AX 2012 R2</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Export sales invoices that contain value-added tax (VAT) to GTS. Import official invoice numbers from GTS to Microsoft Dynamics AX.</p></td>
<td><p>You set up parameters to export sales VAT invoices into text files during or after posting from sales orders. The text file format was user-defined. You imported these text files into GTS. You exported the official invoice numbers into text files and imported them back into Microsoft Dynamics AX.</p></td>
<td><p>By using Microsoft Dynamics AX Application Integration Framework (AIF), you can automatically configure the text file format that is used to export VAT transactions to GTS and then import updated information from GTS to Microsoft Dynamics AX. You can also export additional documents to GTS, such as free-text invoices and project invoices.</p></td>
<td><p>Tax integration with GTS is simplified.</p></td>
</tr>
</tbody>
</table>


## Inventory and product management

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
<th><p>AX 2012 R2</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use a monthly average cost method for inventory costing.</p></td>
<td><p>Not available</p></td>
<td><p>Use a monthly average cost method to post inventory transactions. The monthly average cost method is used to calculate an item’s weighted average cost at the end of the month. This average cost is then used to adjust the transactions for all units of that item that were issued during the month, so that all output transactions for that item during the month have the same unit cost.</p>
<p>Only the monthly average cost from invoiced receipts is calculated, and only invoiced issue transactions are settled. Non-invoiced receipts and issue transactions are calculated and settled in the month when they are invoiced.</p></td>
<td><p>A new inventory costing method is available.</p></td>
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
<th><p>AX 2012 R2</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View and print new inventory summary reports.</p></td>
<td><p>Not available</p></td>
<td><p>Use the <strong>Inventory status report</strong> report to view summarized inventory status. The information on the report includes the beginning quantity, receipt quantity, issued quantity, and end quantity of a specified item. The <strong>Inventory in/out status report</strong> report provides more details than the <strong>Inventory status report</strong> report. For example, the <strong>In</strong> status displays the number of items that are received from a purchase order, production order, transfer order, and physical count, and through other input inventory transactions. The <strong>Out</strong> status displays the number of items that are issued for a sales order, production order, transfer order, and physical count, and through other output inventory transactions. These reports can be queried, and you can select an inventory dimension in the query.</p></td>
<td><p>You can analyze inventory transactions in more detail.</p></td>
</tr>
<tr class="even">
<td><p>Create a GB/T 24589-2010 report.</p></td>
<td><p>You could create a GB/T 19581-2004 report.</p></td>
<td><p>Set up parameters and select information that you can export to an XML file that complies with the accounting software data standards in China.</p></td>
<td><p>This feature helps you comply with updated requirements for regulatory reports.</p></td>
</tr>
</tbody>
</table>


## Additional features

To learn more about additional country-specific features that we added for China, see the tables that apply to your version of the product.

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
<td><p>Tax integration for China</p></td>
<td><p>VAT registration numbers can now be included on customer records.</p></td>
</tr>
<tr class="even">
<td><p>Distribution of subledger lines</p></td>
<td><p>Subledger journal lines are accounting entries that are posted to the general ledger by using the General journal. You can generate subledgers from source documents such as invoices, packing slips, and picking lists for customers and vendors. Before you post the voucher information to the general ledger, you can view or modify subledger journals by using a new method that is named distribution. This method lets you allocate posting amounts among multiple financial dimensions. This method also lets you change the default ledger account number or financial dimension values, based on user permissions.</p>
<p>In China, the Chinese voucher type and Chinese voucher number are implemented in the ledger entries. Chinese voucher types and Chinese voucher numbers are included in the ledger entries after the accounting distributions and subledger journal lines are posted. You can query ledger entries that have Chinese voucher types and voucher numbers by using Chinese ledger inquiries and 16 existing reports for Microsoft SQL Server Reporting Services. You can also print ledger vouchers that have Chinese voucher numbers, and print Chinese financial reports that have Chinese voucher types and voucher numbers.</p>
<p>For more information, see <a href="chn-about-accounting-distributions-and-subledger-journals.md">(CHN) About accounting distributions and subledger journals</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Import ZIP Codes or postal codes for China.</p></td>
<td><p>You can import the Chinese ZIP Codes or postal codes that are published by China Post. You can select to import only the new records, or you can overwrite the available records and add new records.</p>
<p>The name and address format is also updated. The updated address format is country, state, city, district, and street name.</p>
<p>For more information, see <a href="chn-import-zip-postal-codes.md">(CHN) Import ZIP/postal codes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate Asian legal reports in Microsoft Excel for China.</p></td>
<td><p>You can generate external financial statements, such as balance sheets, profit and loss statements, tax reports, and cash flow statements, as Excel worksheets in a single-column or two-column print format. You can use the Asian legal report layout for China to generate these financial statements.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to tax integration for China</p></td>
<td><p>An <strong>External invoice ID</strong> field has been added to the existing <strong>Open customer invoices</strong> list page. You can query and view the sales invoices by using the official VAT invoice number.</p></td>
</tr>
<tr class="even">
<td><p>Tree structure of ledger accounts for China</p></td>
<td><p>In accordance with Chinese legislation, companies must create and maintain charts of accounts in a tree structure of hierarchical accounts by setting up multiple levels for ledger accounts. You can create account numbers in a specific format to indicate the number of levels that you can add to a ledger account. For example, to split a ledger account into two levels, you must use an account number format of xxxx-yy. Here, the first four characters denote the first level, such as a cash account, and the last two characters denote the sublevel, such as a cash account in a currency. The character that separates the various levels of the ledger account is user-defined. In this example, a hyphen (-) is used as the separator character.</p>
<p>For more information, see <a href="chn-set-up-the-hierarchy-structure-for-the-main-account.md">(CHN) Set up the hierarchy structure for the main account</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Ledger accounts of inventory value by site</p></td>
<td><p>In China, organizations that have more than 100 inventory items and maintain several warehouses are required to document inventory values in ledger accounts. These inventory values are organized by sites and item groups. Ledger accounts of the inventory value are categorized by the inventory sites.</p>
<p>In Microsoft Dynamics AX, a company can have multiple sites and inventory locations. You can set up or modify item postings to various ledger accounts for different sites, and you can indicate each inventory item group. You can also activate combinations of inventory transactions for sites, and then post the site details in the sales orders, purchase orders, inventory journals, or production journals. You can view the ledger accounts by the inventory value of each site in the <strong>Chart of accounts</strong> form.</p>
<p>When you post the invoices and journals, the following ledger transactions are updated:</p>
<ul>
<li><p>When you post sales orders, the ledger transactions are applied to the correct accounts for packing slips and invoices.</p></li>
<li><p>When you post purchase orders, ledger transactions are applied to the correct accounts for purchase packing slips, invoices, or return orders.</p></li>
<li><p>When you post purchase orders and end production orders for inventory items of the standard cost model, the ledger account is selected based on the setup in the <strong>Posting</strong> form.</p></li>
<li><p>When you post the Inventory Movement, Profit and Loss, Bills of Materials, Item Arrival, Production Input, Physical Counting, Tag Counting, or Project Item journals, the ledger account is selected based on the setup in the <strong>Item posting</strong> form.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="https://technet.microsoft.com/library/jj664101(v=ax.60)">(CHN) Chart of accounts (modified form)</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/jj664026(v=ax.60)">(CHN) Item posting (modified form)</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Comparison of bill of materials (BOM) versions for China</p></td>
<td><p>A product can contain many versions of its BOM during its life cycle. You can use the <strong>BOM comparison</strong> form to identify the differences between several versions of a product. You can also compare and highlight differences in components among a group of similar products and different products. This functionality can help you more effectively answer customer inquiries about differences in your products and the uses of your products, and can improve overall productivity and operational efficiency.</p>
<p>For more information, see <a href="chn-about-bom-comparison.md">(CHN) About BOM comparison</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to bank account reconciliation and the fiscal calendar for China</p></td>
<td><p>You can reconcile bank statements for bank accounts that are active. You cannot change the bank account status to inactive if the account has any reconciliation journals that are open.</p>
<p>You can also validate the closing of accounting periods in the <strong>Ledger calendar</strong> form.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj664094(v=ax.60)">(CHN) Ledger calendar (modified form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Maintain China-specific information in legal entities and the chart of accounts.</p></td>
<td><p>You can use two new China-specific forms that are attached in the legal entities and the chart of accounts to set up China-specific information.</p>
<p>For more information, see <a href="chn-set-up-the-hierarchy-structure-for-the-main-account.md">(CHN) Set up the hierarchy structure for the main account</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to Chinese vouchers</p></td>
<td><p>In accordance with Chinese accounting practices, voucher numbers must be sequential for Chinese vouchers. You can verify whether Chinese voucher numbers are sequential and then renumber the vouchers to maintain the continuity of Chinese voucher numbers. You can generate a report to view the history of the renumbered vouchers.</p>
<p>You can also perform the following tasks:</p>
<ul>
<li><p>Print vouchers from the <strong>Journal voucher</strong> form. You can print a voucher either before or after you post it. You can print a voucher before you post it by using the pro forma posting option. Only the information that is generated after the voucher is posted is printed.</p></li>
<li><p>Create a general journal and journal lines in the <strong>Chinese vouchers</strong> form. You can approve and post a single voucher or multiple vouchers.</p></li>
</ul>
<p>For more information, see <a href="chn-about-chinese-vouchers.md">(CHN) About Chinese vouchers</a>.</p></td>
</tr>
<tr class="even">
<td><p>Import bank statements for reconciliation against the statement information that is stored in Microsoft Dynamics AX.</p></td>
<td><p>You can now import bank statements in various formats, reconcile the imported bank statements, and match statement lines with booked bank documents.</p></td>
</tr>
<tr class="odd">
<td><p>Inventory summary reports for China</p></td>
<td><p>Chinese companies use the <strong>Inventory status</strong> report to view summarized inventory status. The information on this report includes the beginning quantity, receipt quantity, issued quantity, and end quantity of a specified item. The <strong>Inventory in/out status</strong> report is another frequently used inventory report that offers more details than the <strong>Inventory status</strong> report. These reports can be queried, and there is an option that lets you set the inventory dimension.</p>
<p>You can use the following reports to check the inventory movements of receipts and issues in a warehouse:</p>
<ul>
<li><p><strong>Inventory status</strong> report − Shows the beginning quantity, in quantity, out quantity, and end quantity of inventory items for a specified period.</p></li>
<li><p><strong>Inventory in/out status</strong> report − Shows the detailed <strong>In</strong>/<strong>Out</strong> status of inventory items for a specified period.</p></li>
</ul>
<p>For example, the <strong>In</strong> status displays the number of items that are received from a purchase order, production order, transfer order, and physical count, and through other input inventory transactions. The <strong>In</strong> status includes purchased in, transferred in, or produced in quantities. The <strong>Out</strong> status displays the number of items that are issued for a sales order, production order, transfer order, and physical count, and through other output inventory transactions. By using this information, you can view the detailed <strong>In</strong>/<strong>Out</strong> status of the inventory items for a specified period.</p>
<p>If a specific period is not selected, the first date of the current month is used as the starting date, and the current date is used as the ending date.</p>
<p>For more information, see <a href="chn-inventory-and-warehouse-management-reports.md">(CHN) Inventory and warehouse management reports</a>.</p></td>
</tr>
<tr class="even">
<td><p>Issue VAT invoices by using a free text invoice.</p></td>
<td><p>You can now issue VAT invoices from the <strong>Free-text invoice</strong> form.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj664126(v=ax.60)">(CHN) Free text invoice (modified form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Report information for GB/T 24589-2010 in China</p></td>
<td><p>Set up parameters, and select information that you can export to an XML file for the accounting software data standards in China.</p>
<p>For more information, see <a href="chn-key-tasks-set-up-and-export-financial-information-for-gb-t-24589-2010.md">(CHN) Key tasks: Set up and export financial information for GB/T 24589-2010</a>.</p></td>
</tr>
<tr class="even">
<td><p>Financial dimension attributes for China</p></td>
<td><p>You can define several financial dimension attributes, in addition to the department, cost center, and purpose, to view and modify account and journal information.</p>
<p>In China, you can use the additional financial dimensions for the Chinese bank reconciliation journal and for the Chinese voucher system. The following reports can use the new dimensions:</p>
<ul>
<li><p>Account analysis by dimensions</p></li>
<li><p>Account balance sheet by dimensions</p></li>
<li><p>Chart of account by dimensions</p></li>
<li><p>Detailed ledger transactions by dimensions</p></li>
<li><p>Ledger transactions by dimensions</p></li>
<li><p>Vendor balance by dimensions</p></li>
<li><p>Customer balance by dimensions</p></li>
<li><p>Matrix report by dimensions</p></li>
</ul>
<p>For more information, see <a href="chn-general-ledger-reports.md">(CHN) General ledger reports</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Updates to the Chinese vouchers</p></td>
<td><p>You can enter the account and dimension attribute together for a transaction. You can specify a unique set of dimensions for the combinations of main and offset accounts when transactions are created. For China, when you enter Chinese vouchers, you can enter ledger accounts and dimension values together, and validate these details against the accounting rules before you post the vouchers.</p>
<p>For more information, see <a href="chn-about-chinese-vouchers.md">(CHN) About Chinese vouchers</a>.</p></td>
</tr>
<tr class="even">
<td><p>Monthly average cost for China</p></td>
<td><p>The monthly average cost method is an inventory costing method that is based on the weighted average principle. According to the weighted average principle, items that are issued from inventory are valued based on the average value of items that are received into inventory during each month of the inventory closing period. The monthly average cost method resembles the weighted average cost by date method. However, the monthly average cost method is calculated by month instead of by using a specific date.</p>
<p>The monthly average cost method is used to calculate a specific item’s weighted average cost at the end of the month. This average cost is then used to adjust the transactions for all the units of that item that were issued during the month, so that all output transactions for that item during the month have the same unit cost.</p>
<p>Only the monthly average cost from invoiced receipts is calculated, and only invoiced issue transactions are settled. Non-invoiced receipts and issue transactions are calculated and settled in the month when they are invoiced.</p>
<p>For more information, see <a href="chn-about-the-monthly-average-cost-model.md">(CHN) About the monthly average cost model</a>.</p></td>
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
<td><p>Allocate fixed asset depreciation costs to multiple organization units, and track the transfer history.</p></td>
<td><p>You can set up allocation rules to allocate and share the depreciation costs of fixed assets among organization units that have used the asset. You can also track the movement of an asset to a new location.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="chn-jpn-create-allocation-rules-and-allocate-depreciation-costs.md">(CHN, JPN) Create allocation rules and allocate depreciation costs</a></p></li>
<li><p><a href="chn-jpn-allocation-rules-for-fixed-assets.md">(CHN, JPN) Allocation rules for fixed assets</a></p></li>
<li><p><a href="chn-transfer-fixed-assets-to-a-new-location.md">(CHN) Transfer fixed assets to a new location</a></p></li>
<li><p><a href="chn-jpn-fixed-asset-location-transfer-history.md">(CHN, JPN) Fixed asset location transfer history</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Chinese tax integration for VAT customer invoices</p></td>
<td><p>You can generate VAT customer invoices, and then export text files that use the GTS format from Microsoft Dynamics AX. You can then import reference numbers for the VAT customer invoices that can be linked to the original invoices.</p>
<p>Before you export a VAT customer invoice, you can split the VAT customer invoice to create multiple invoice documents. You can also combine multiple VAT customer invoices to create one invoice export document that contains the line details of the original invoices.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="chn-chinese-tax-integration-for-vat-customer-invoices.md">(CHN) Chinese tax integration for VAT customer invoices</a></p></li>
<li><p><a href="chn-configure-tax-integration.md">(CHN) Configure tax integration</a></p></li>
<li><p><a href="chn-export-vat-customer-invoices-or-import-invoice-reference-numbers.md">(CHN) Export VAT customer invoices or import invoice reference numbers</a></p></li>
<li><p><a href="chn-split-or-combine-vat-customer-invoices.md">(CHN) Split or combine VAT customer invoices</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Calculate payment fees by using a bank payment rule.</p></td>
<td><p>You can create a bank payment rule to calculate bank payment fees for a vendor payment. You can assign the bank payment rule to a payment fee that you set up. You can then create and post a payment journal by using the payment fee that has the bank payment rule that you assigned. Microsoft Dynamics AX calculates the payment fees based on the association that you create between the bank payment rule and the payment fee.</p>
<p>For more information, see <a href="chn-set-up-and-calculate-the-bank-payment-fees.md">(CHN) Set up and calculate the bank payment fees</a>.</p></td>
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
<td><p>Maintain the transfer history for fixed assets.</p></td>
<td><p>You can update and maintain the transfer history for a fixed asset that you transfer from one location to another. The transfer history contains the current location of the fixed asset, the new location of the fixed asset, the date of the transfer, and comments, if any comments have been entered. The transfer history information for fixed assets is included in the financial data that you export for the GB/T 24589 report.</p>
<p>For more information, see <a href="chn-transfer-fixed-assets-to-a-new-location.md">(CHN) Transfer fixed assets to a new location</a>.</p></td>
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
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Generate a user operation log for transactions and voucher changes.</p></td>
<td><p>You can generate a user operation log to audit user activity for transactions and voucher changes in Microsoft Dynamics AX.</p>
<p>For more information, see <a href="chn-generate-a-user-operation-log-for-transactions-and-voucher-changes.md">(CHN) Generate a user operation log for transactions and voucher changes</a>.</p></td>
</tr>
</tbody>
</table>

  


