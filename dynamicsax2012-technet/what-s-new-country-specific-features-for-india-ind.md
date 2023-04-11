---
title: "What's new: Country-specific features for India (IND)"
TOCTitle: Country-specific features for India
ms:assetid: 257c80ed-5b1c-4f45-8c5b-c85aea27ff9c
ms:mtpsurl: https://technet.microsoft.com/library/Dn507150(v=AX.60)
ms:contentKeyID: 59623233
author: tonyafehr
ms.date: 06/09/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for India (IND) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we changed and added country-specific functionality for India. This topic is divided into two sections. The first section outlines the key features that have a broad impact on Indian installations, such as features that affect export/import (EXIM) incentive schemes, taxation, invoicing, general ledger, and fixed assets. The second section describes additional changes to country-specific functionality for India. For more information about specific features for India, see [TechNet Library for Application Users - India](https://go.microsoft.com/fwlink/?linkid=299913).

## Key features for India

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

The Government of India offers many special incentive schemes to Indian importers. These schemes are mostly available for imported products that are used to manufacture export goods. You have more flexibility when you post and report import and export activity and the related customs duty taxes.

You can set up tax numbers and other details to track and report transactions that contain Tax Deducted at Source (TDS) and Tax Collected at Source (TCS) by financial dimension and by legal entity.

Create free text invoices to record purchases that are not related to a purchase order. Add free text lines to an invoice that was created from a purchase order. You can add direct and indirect taxes to free text lines. You can also make corrections to import and export transaction documents, such as sales orders, instead of canceling the transaction and then recreating the document for the transaction.

By using the subledger journal in AX 2012 R2, you can review transactions before you post them. You can also create additional financial dimensions to allocate costs more effectively.

Transfer fixed assets to multiple legal entities and financial dimensions. You can track fixed asset transfers and report them to your local authority.

## Comparison with Microsoft Dynamics AX 2009

These features have changed considerably since AX 2009. AX 2012 R2 includes changes to the following areas:

  - EXIM incentive schemes

  - Taxation

  - Invoicing

  - General ledger

  - Fixed assets

## EXIM incentive schemes

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
<td><p>Optionally, post customs duty taxes to expenses instead of the cost of inventory.</p></td>
<td><p>Customs duty taxes were posted to the cost of inventory.</p></td>
<td><p>By default, customs duty taxes for an imported inventory item are posted to the cost of the item. When you select the <strong>Charge as expense ratio</strong> option for customs duty and EXIM taxes, the related customs duty is charged to an expense account.</p></td>
<td><p>You can post all or part of customs duty taxes to an expense account.</p></td>
</tr>
<tr class="even">
<td><p>Update the daily stock account (DSA) register for manufactured items.</p></td>
<td><p>The DSA register was updated for the quantity of finished items that was sold. The excise duty that was related to the items was not updated automatically.</p></td>
<td><p>When an export sales order is posted, the DSA register is updated automatically with the quantity of finished goods in the bill of materials (BOM) and the related excise duty.</p></td>
<td><p>The tracking and reporting of export orders by using the DSA register are simplified.</p></td>
</tr>
</tbody>
</table>


## Taxation

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
<td><p>Adjust indirect taxes on a product that is returned to a vendor.</p></td>
<td><p>Not available</p></td>
<td><p>When stocked and non-stocked products are returned to a vendor, you can calculate and post an adjustment to the related indirect taxes on the products.</p></td>
<td><p>Adjustments to indirect taxes for purchase order returns and credits are simplified.</p></td>
</tr>
<tr class="even">
<td><p>Adjust indirect taxes on a product that is returned by a customer.</p></td>
<td><p>Not available</p></td>
<td><p>When stocked and non-stocked products are returned to you by a customer, you can calculate and post an adjustment to the related indirect taxes on the products.</p></td>
<td><p>Adjustments to indirect taxes for sales order returns and credits are simplified.</p></td>
</tr>
<tr class="odd">
<td><p>Enter entity-specific tax information for the legal entities in your organization.</p></td>
<td><p>Not available</p></td>
<td><p>When you set up a legal entity for your organization, you can enter tax information that is specific to the location of the legal entity. For example, you can enter the permanent account number (PAN) and withholding tax details in the <strong>Legal entities</strong> form. When you create taxable transactions for the legal entity, the tax information is automatically added to a form, based on the values that you entered for the legal entity.</p></td>
<td><p>It is easier to add default tax values to transactions for a legal entity.</p></td>
</tr>
<tr class="even">
<td><p>Enter a tax registration number for a specific address.</p></td>
<td><p>You added a tax registration number for an organization.</p></td>
<td><p>In the global address book (GAB), you can enter a tax registration number for each address. You can also enter direct and indirect tax registration numbers for customers, vendors, and legal entities in the <strong>Enterprise tax registration numbers</strong> form. You can specify whether a tax registration number is shared by multiple addresses. The tax registration number is automatically added to transactions for the related address.</p></td>
<td><p>It is easier to identify transactions by address for tax reporting purposes.</p></td>
</tr>
<tr class="odd">
<td><p>Add direct and indirect taxes to project and service transactions, billing processes, and tax settlements. Adjust transactions that are posted that have incorrect tax groups. View tax calculations for a customer invoice proposal before you send the invoice to the customer.</p></td>
<td><p>Not available</p></td>
<td><p>Support for the calculation of India taxes in <strong>Project management and accounting</strong> is integrated for primary documents such as purchase orders, purchase requisitions, and requests for quotation, and also for adjustments. The following tax types are supported:</p>
<ul>
<li><p>Service tax</p></li>
<li><p>Value-added tax (VAT)</p></li>
<li><p>India sales tax</p></li>
<li><p>Excise tax</p></li>
<li><p>Customs</p></li>
<li><p>TDS</p></li>
<li><p>TCS</p></li>
</ul></td>
<td><p>Tax calculations for project and service management transactions are simplified.</p></td>
</tr>
<tr class="even">
<td><p>Set up a bill of entry (BOE) number that the customs authority provides. Attach the BOE number to a purchase order when the purchase order is posted.</p></td>
<td><p>You created an invoice for a product receipt or an import order, but did not receive confirmation of the amount of tax that was calculated for the related BOE.</p></td>
<td><p>Optionally, you can post a product receipt and an invoice by associating the quantity and invoice number in a BOE journal. You can remove an invoice registration provided that the related BOE is not posted. You can also cancel part or all of a BOE if the BOE is not posted.</p></td>
<td><p>It is easier to review and correct taxes for a BOE that is associated with an import order.</p></td>
</tr>
</tbody>
</table>


## Invoicing

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
<td><p>Add tax details to invoice lines. Calculate direct and indirect taxes on free text invoices.</p></td>
<td><p>Tax details were entered only for invoices that were created from a purchase order.</p></td>
<td><p>Create an invoice line that is not related to a purchase order on an invoice. You can enter tax details, such as TDS, TCS, India sales tax, VAT, and other taxes, on these invoice lines. You can also create a recurring invoice, and calculate direct and indirect taxes for the amount in the recurring invoice. All details that are required to generate recurring invoices can be specified in the <strong>Free text invoice templates</strong> form.</p></td>
<td><p>The calculation of taxes on free text lines and free text invoices is more flexible.</p></td>
</tr>
<tr class="even">
<td><p>Create, modify, and reverse a free text invoice.</p></td>
<td><p>Not available</p></td>
<td><p>Define the maximum retail price per unit for an item in the <strong>Free text invoice</strong> form, and calculate the tax based on the amount per unit. When excise transactions from the free text invoice are posted, the excise registers are updated with the quantity details.</p>
<p>Correct a free text invoice that has been posted. You can also update the following tax information in the invoice:</p>
<ul>
<li><p>Update excise registers with details of corrected invoices or canceled invoices.</p></li>
<li><p>Reverse service tax entries when the invoice correction is performed for a settled invoice.</p></li>
<li><p>Reverse TCS entries when the invoice correction is performed after the TCS on an original invoice is settled.</p></li>
</ul></td>
<td><p>Purchases for items and services that are not related to a purchase order are simplified.</p></td>
</tr>
<tr class="odd">
<td><p>Make corrections to a packing slip for a sales order.</p></td>
<td><p>Not available</p></td>
<td><p>Correct or cancel a line in a packing slip for a sales order.</p></td>
<td><p>You can make corrections to a packing slip without having to cancel and re-create the packing slip.</p></td>
</tr>
<tr class="even">
<td><p>Make and track corrections to an import purchase order.</p></td>
<td><p>Not available</p></td>
<td><p>Modify lines in an import purchase order that is not posted. Review the modifications in the import order before it is accepted or rejected.</p></td>
<td><p>You can make corrections to an import purchase order without having to cancel and re-create the import order.</p></td>
</tr>
</tbody>
</table>


## General ledger

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
<td><p>Distribute transaction amounts, and even taxes, to more financial dimensions.</p></td>
<td><p>You could create 10 financial dimensions. These financial dimensions included three predefined dimensions for department, cost center, and purpose.</p></td>
<td><p>Transaction amounts can be distributed among more than 10 dimensions. These dimensions include the three predefined financial dimensions. As part of the functionality for subledger journals and distributions, the accounting entries for the dimension amounts can be verified before the amounts are posted to general ledger accounts.</p></td>
<td><p>You have more flexibility for tracking and reporting transactions by financial dimension.</p></td>
</tr>
<tr class="even">
<td><p>View direct and indirect tax transactions together with accounting entries in subledger journals, and distribute the tax amount among the various dimensions.</p></td>
<td><p>Not available</p></td>
<td><p>As part of the functionality for subledger journals and distributions, allocate customs duty amounts to multiple financial dimensions. Verify the accounting entries for the EXIM customs duty amounts in transactions before the amounts are posted to general ledger accounts.</p></td>
<td><p>It is easier to track and report tax amounts.</p></td>
</tr>
<tr class="odd">
<td><p>Adjust direct tax entries by using the <strong>Withholding tax journal</strong> that is generated from the general ledger.</p></td>
<td><p>You adjusted tax liability general ledger accounts by passing adjustment entries by using the <strong>Withholding tax journal</strong> in <strong>General ledger</strong>. Alternatively, you adjusted the original source document by using a credit note, for example.</p></td>
<td><p>In the <strong>Withholding tax journal</strong>, you can specify the details for increasing or decreasing a tax transaction. You can also recalculate the tax amount and then post the information to the general journal. Additionally, you can link the adjustment entry with the appropriate parent transaction. The reports then net off the overall result to reflect the change in tax liability that corresponds to the specific document.</p></td>
<td><p>Adjustments to withholding tax are simplified.</p></td>
</tr>
<tr class="even">
<td><p>Select the types of exchange rates that are used to calculate the customs duties for import and export transactions.</p></td>
<td><p>A separate tab for customs exchange rates was available in the <strong>Exchange rates</strong> form.</p></td>
<td><p>You can define customs exchange rates separately in the <strong>Ledger</strong> form for import and export transactions. You can set up the rates that are used by default. The default exchange rates can then be modified for specific transactions.</p></td>
<td><p>The calculation of exchange rates for India export and import transactions is simplified.</p></td>
</tr>
<tr class="odd">
<td><p>Set up number sequences for additional transaction types.</p></td>
<td><p>You could set up number sequences for some EXIM incentive schemes.</p></td>
<td><p>Set up number sequences for EXIM incentive schemes, withholding tax settlement, VAT deferment, export shipping documents, goods receipt notes, and excise registers.</p></td>
<td><p>It is easier to track and report EXIM transactions.</p></td>
</tr>
</tbody>
</table>


## Fixed assets

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
<td><p>Transfer fixed assets among various dimension values for a selected value model.</p></td>
<td><p>Not available</p></td>
<td><p>You can transfer a fixed asset to another financial dimension. However, if the fixed asset is associated with a fixed asset group for which depreciation is calculated at the group level, the accumulated depreciation and net book value for the transferred asset are not identified. The value models that are associated with a fixed asset for which the <strong>Asset group depreciation</strong> check box is selected must be filtered out of the <strong>Fixed asset transfer</strong> form.</p></td>
<td><p>This feature enables fixed asset transfers, to comply with Indian depreciation requirements.</p></td>
</tr>
</tbody>
</table>


## Additional features

For more information about additional country-specific features that we added for India, see the tables that apply to your version of the product.

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
<td><p>The message about thresholds that are exceeded was removed from India direct tax.</p></td>
<td><p>In earlier versions, error and warning messages about threshold validations can be set up to notify users when the cumulative transaction amount exceeds the threshold for direct tax (TDS/TCS). In AX 2012 R2, this functionality has been deprecated.</p>
<div class="alert">

> [!NOTE]
> <P>The threshold functionality is not deprecated. Only the error and warning messages have been removed.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Depreciation calculation for India</p></td>
<td><p>In accordance with the Indian companies act, depreciation of assets is calculated based on the number of days in a period, the type of industry, and the type of shift. You can calculate depreciation of assets based on the number of days that the asset is used by using the following methods:</p>
<ul>
<li><p>The <strong>Straight line percentage</strong> method</p></li>
<li><p>The written down value method (or the <strong>Reducing balance</strong> method)</p></li>
<li><p>The monthly depreciation that is calculated based on the actual number of days in a month</p></li>
</ul>
<p>For India, a straight line percentage method has been added. The <strong>Straight line percentage</strong> depreciation method. Depreciation is calculated by using the number of days, and is displayed in the <strong>Depreciation profiles</strong> form for a value model for the selected depreciation method and calendar type. If you select the reducing balance method as a value model for the current layer, you can use both the standard depreciation calculation process and the day-based depreciation calculation process. You can attach either a standard calendar or a day-based calendar when the depreciation profile uses the reducing balance method.</p>
<p>Depreciation for seasonal and non-seasonal industries is calculated by using the <strong>Min. working days for seasonal industries</strong> parameter. The following factors are considered when shift depreciation is calculated:</p>
<ul>
<li><p>The type of shift and industry.</p></li>
<li><p>The rate of shift depreciation.</p></li>
<li><p>The posting layer for the value model record must be <strong>Current</strong>, and the calendar type must be <strong>Day based</strong>.</p></li>
</ul>
<p>The calculated shift depreciation for the value model is displayed separately for each type of shift. For single-shift depreciation, the calendar type should be <strong>Day based</strong> for a value model for the current layer, and the depreciation method is <strong>Straight line percentage</strong> or <strong>Reducing balance</strong> method.</p>
<p>For more information, see <a href="ind-setting-up-depreciation.md">(IND) Setting up depreciation</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Financial dimensions for India</p></td>
<td><p>You can define unlimited financial dimensions and use those financial dimensions as account segments in the chart of accounts. You can define financial dimensions for tax ledger groups, direct and indirect tax inquiries, EXIM incentive schemes, and stock transfers.</p></td>
</tr>
<tr class="even">
<td><p>EXIM Export Promotion Capital Goods (EPCG) incentive scheme</p></td>
<td><p>Under the EPCG scheme, a license holder can import capital goods. These capital goods include computer hardware and software. The validity period for the import of capital goods under a 0 (zero) percent EPCG scheme is nine months. You can extend the export obligation period for two years one time, and this extension is subject to specific conditions. The export obligation is equivalent to six times the duty that is saved on the capital goods that are imported under the EPCG scheme, and the export obligation must be fulfilled in six years from the issue date of the authorization.</p>
<p>A concessional 3-percent duty EPCG scheme allows for an export obligation that is equivalent to eight times the duty that is saved on capital goods that are imported under the EPCG scheme, and the export obligation must be fulfilled in eight years. For EPCG authorizations that have a duty saved amount of INR 100 crores or more, the export obligation can be fulfilled over a period of 12 years.</p>
<p>Companies that operate under the Board for Industrial &amp; Financial Reconstruction (BIFR) and units in Agricultural Export zones are also granted 12 years to fulfill their export obligations. Merchant exporters can import capital goods under the EPCG scheme if the capital goods are installed in the factory of the supporting manufacturer who is endorsed on the license. An EPCG authorization holder can also obtain machinery and equipment from India, and the Indian manufacturer can import components for the machinery at a concessional rate of either 0 percent or 3 percent. However, the license holder, not the manufacturer, is responsible for meeting the export obligation.</p>
<p>For more information, see <a href="ind-exim-export-promotion-capital-goods-epcg-incentive-scheme-transactions.md">(IND) EXIM Export Promotion Capital Goods (EPCG) incentive scheme transactions</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to the electronic file format for TDS and TCS statements</p></td>
<td><p>In accordance with Indian tax legislation, legal entities must submit quarterly TDS and TCS statements in the electronic format to the National Securities Depository Limited (NSDL).</p>
<p>The electronic TDS and TCS statements must include the type of deductor, the name of the utility that is used for return preparation, the transfer voucher number, the details of the third parties from whom the tax is deducted or collected, and the challan details that are related to the deposit of tax at government-authorized bank branches.</p>
<p>Government entities must generate the TDS and TCS statements in the electronic file format that includes the following additional details:</p>
<ul>
<li><p><strong>Ministry details</strong> – The ministry that the government entity belongs to.</p></li>
<li><p><strong>Pay and Account Officer (PAO) code</strong> – A six-character alphanumeric code.</p></li>
<li><p><strong>PAO registration number</strong> – A seven-digit registration number.</p></li>
<li><p><strong>Drawing and Disbursing Officer (DDO) code</strong> – A ten-character alphanumeric code.</p></li>
<li><p><strong>DDO registration number</strong> – A ten-digit registration number.</p></li>
</ul>
<p>The regular or correction electronic TDS and TCS statement files must be validated by the File Validation Utility (FVU) tool before the statements are submitted to NSDL. The FVU tool verifies the challan details that are quoted in the electronic TDS and TCS statements against the challan details that are uploaded by banks. If the challan details do not match, a warning file is generated that contains the details of the mismatch.</p>
<p>For more information, see <a href="ind-setting-up-tax-deducted-at-source-tds.md">(IND) Setting up Tax Deducted at Source (TDS)</a> and <a href="ind-setting-up-tax-collected-at-source-tcs.md">(IND) Setting up Tax Collected at Source (TCS)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to import orders for India</p></td>
<td><p>You can increase the quantity of an item on an import order line after you update the invoice registration for the order. You cannot decrease the quantity of an item on an import order line after you update the invoice registration for the order. The updated quantity on the import order line must be less than the BOE quantity that is already posted for the item.</p>
<p>You can view the updated import order in the <strong>Invoice registration</strong> form.</p>
<p>When you post the BOE for an import order, the <strong>Bill of entry</strong> check box is selected for the order line in the <strong>Invoice registration</strong> form. You cannot delete the import order line from the <strong>Invoice registration</strong> form if the <strong>Bill of entry</strong> check box is selected for the order line.</p>
<p>For more information, see <a href="ind-update-the-import-order-line-quantity-after-updating-the-invoice-registration.md">(IND) Update the import order line quantity after updating the invoice registration</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable and accounts payable invoices</p></td>
<td><p>You can create and enter an invoice line that is not related to a purchase order on an invoice. You can enter details for the following taxes on these invoice lines:</p>
<ul>
<li><p>TDS</p></li>
<li><p>TCS</p></li>
<li><p>India sales tax</p></li>
<li><p>VAT</p></li>
<li><p>Excise</p></li>
<li><p>Service tax</p></li>
</ul>
<p>You can also create a recurring invoice, and calculate direct and indirect taxes for the amount on the recurring invoice. All details that are required to generate recurring invoices can be specified in the <strong>Free text invoice templates</strong> form.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj664903(v=ax.60)">(IND) Free text invoice templates (modified form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Fixed asset transfer for India</p></td>
<td><p>You can transfer fixed assets between dimension values for a selected value model by using accounting entries. In accordance with the requirements of the India Income Tax Act, fixed assets are accounted and depreciated by using the concept of the block of assets. Fixed assets that share characteristics are grouped into blocks of assets, based on the guidelines in the India Income Tax Act. When an individual asset is associated with a block of assets, which is identified as a fixed asset group in Microsoft Dynamics AX, the individual asset loses its identity and is merged with the asset group value. Depreciation is applied on the value of the whole fixed asset group and is not calculated on individual asset values.</p>
<p>The system cannot identify the depreciation value and net book value for an individual fixed asset that is being transferred, if that asset is associated with a fixed asset group value model for which asset group depreciation applies. Therefore, the value models that are associated with a fixed asset for which the <strong>Asset group depreciation</strong> check box is selected must be filtered out of the <strong>Fixed asset transfer</strong> form.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh209220(v=ax.60)">Transfer fixed assets (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Uptake of the subledger journal and distribution framework with Indian direct tax</p></td>
<td><p>The Indian functionality that is used to account for TDS and TCS direct tax amounts has been applied to the subledger journal and distribution framework. Therefore, the new monetary amount, withholding tax, has been introduced, and TDS and TCS direct tax amounts can be distributed between dimensions, based on the distribution of the source amount on the original source document line. As part of the functionality for subledger journals and distributions, the accounting entries for the TDS and TCS tax amounts can be verified before the amounts are posted to general ledger accounts.</p>
<p>This functionality applies to direct tax amounts that are based on purchase orders, vendor invoices, and free text invoices.</p>
<p>For more information, see <a href="ind-about-accounting-distributions-and-subledger-journals.md">(IND) About accounting distributions and subledger journals</a>.</p></td>
</tr>
<tr class="even">
<td><p>The method that is used to adjust direct tax entries that are posted to the general ledger has changed. This feature replaces the feature for TDS and TCS adjustment, which is now deprecated.</p></td>
<td><p>Adjust direct tax entries by using the Withholding tax journal that is generated from the general ledger. In the Withholding tax journal, you can specify the details for adjusting a direct tax transaction, recalculate the tax amount, and then transfer the information to the general journal.</p>
<p>For more information, see <a href="ind-settle-withholding-tax-payments-and-enter-withholding-tax-challan-information.md">(IND) Settle withholding tax payments and enter withholding tax challan information</a> and <a href="https://technet.microsoft.com/library/jj664896(v=ax.60)">(IND) Create withholding tax journal (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Manual adjustment of taxes</p></td>
<td><p>You can manually adjust recoverable tax values for each transaction. This functionally is used mainly to settle taxes. You can make the adjustments for recoverable tax transactions or payable transactions that have been posted by tracking the original record or by creating a new adjustment transaction. You can create and settle transactions that have excise and VAT recoverable amounts in the <strong>Purchase order</strong> form. You can create and settle transactions that have excise and VAT payable amounts in the <strong>Sales order</strong> form. You can create transactions that have service tax recoverable amounts or service tax payable amounts, and settle those transactions in a payment journal. You can compare recoverable and payable amounts, and adjust them in the <strong>Transactions</strong> form.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj664489(v=ax.60)">(IND) Create sales order (modified form)</a> and <a href="https://technet.microsoft.com/library/jj664764(v=ax.60)">(IND) Transactions (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Subledger journal impact on the Indian excise duty functionality</p></td>
<td><p>The subledger accounting distribution framework affects the Indian functionality for excise duty. The subledger accounting distribution framework lets you obtain an overview of the distribution on cost centers before you post an amount to ledger accounts. Postings of the following types are included:</p>
<ul>
<li><p>Deferred amounts for excise duty on the value of goods that are not allowed to be claimed as recoverable in the year of purchase</p></li>
<li><p>Credit note transactions that have combinations of excise amounts that include central value-added tax (CENVAT)</p></li>
<li><p>Tax adjustment amounts that are registered on purchase order invoices, free text invoices, and purchase order credit notes</p></li>
</ul>
<p>For more information, see <a href="ind-about-accounting-distributions-and-subledger-journals.md">(IND) About accounting distributions and subledger journals</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Change to the item type for India</p></td>
<td><p>You can specify the item type of an item as <strong>Item</strong> or <strong>Service</strong> instead of <strong>BOM</strong>.</p>
<p>Goods that are manufactured by an entity are updated in the DSA register, based on the <strong>Default order type</strong> - <strong>Production</strong> value that is set for an item. Additionally, the item details in the <strong>SION</strong> form and the <strong>EXIM Authorization schemes</strong> design are updated based on the <strong>Default order type</strong> - <strong>Production</strong> value that is set for an item. You can specify the default order type for an item.</p>
<p>For more information, see <a href="ind-setting-up-sion-in-inventory-management.md">(IND) Setting up SION in Inventory management</a>.</p></td>
</tr>
<tr class="even">
<td><p>BOE information is evaluated on a line-by-line basis.</p></td>
<td><p>In AX 2012 R2, each line in a BOE is calculated for taxes, posted, and recorded individually.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj677988(v=ax.60)">(IND) Bill of entry journal (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Standard Input Output Norms (SION)</p></td>
<td><p>The Government of India offers many special incentive schemes to Indian importers. These schemes are mostly available for imported products that will be used to manufacture export goods. SION, which is published and issued by the Directorate General of Foreign Trade (DGFT), contains guidelines that apply to the types of inputs, or materials, that importers can import without paying a customs duty. These inputs must be used to manufacture standardized exportable products. Licenses that are issued under the Duty Exemption Scheme are based on SION. For example, licenses for some incentive schemes, such as the Advance Authorization (AA) and Duty Free Import Authorization (DFIA), are issued only for products that are contained in the SION table.</p>
<p>The SION table contains a list of inputs that importers can import without paying a customs duty, based on the following factors:</p>
<ul>
<li><p>Percentage content of materials</p></li>
<li><p>Net plus percentage of wastage</p></li>
<li><p>Percentage of FOB (Free on Board) value of export</p></li>
<li><p>Net to Net (without any wastage)</p></li>
<li><p>Actual consumption basis</p></li>
</ul>
<p>For more information, see <a href="ind-setting-up-sion-in-inventory-management.md">(IND) Setting up SION in Inventory management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements for purchase orders and sales orders for India</p></td>
<td><p>You can allocate miscellaneous charges for a purchase order to selected purchase order lines. You can allocate miscellaneous charges by using the whole amount and per invoice allocation methods.</p>
<p>You can update or review the tax information for a purchase order or sales order in the <strong>Purchase agreement</strong> - <strong>Release order lines</strong> form or the <strong>Sales agreement</strong> - <strong>Release order lines</strong> form.</p>
<p>When you post a BOE, you can specify the reason code and comments for any changes that you make in an import purchase order.</p>
<p>When you run the purchase order year-end process (opening or closing), the withholding taxes are not considered.</p>
<p>For more information, see <a href="ind-manage-purchase-or-sales-agreements-and-release-orders.md">(IND) Manage purchase or sales agreements and release orders</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Open customer invoices and settlement enhancements for India</p></td>
<td><p>You can view a summary of open invoice transactions, invoice amounts, references, payments, interest, and fees that are associated with the invoices and balances at the invoice level and the invoice line level. You can also select which invoice lines to settle when a partial payment is made. In addition, for India, you can view the actual amount, the TCS payable, and the TDS receivable for an invoice separately.</p>
<p>You can also view the selected partial payment lines. The TDS amount and the TCS amount are displayed in separate columns for the invoice lines.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="ind-maintain-tcs-transactions-for-accounts-receivable.md">(IND) Maintain TCS transactions for Accounts receivable</a></p></li>
<li><p><a href="ind-maintain-tcs-transactions-for-accounts-payable.md">(IND) Maintain TCS transactions for Accounts payable</a></p></li>
<li><p><a href="ind-maintain-tds-transactions-for-accounts-payable.md">(IND) Maintain TDS transactions for Accounts payable</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Recalculation of indirect taxes that is triggered by specific conditions</p></td>
<td><p>In AX 2012 R2, the uncommitted tax table is introduced. The purpose of this table is to improve system performance by preventing the system from recalculating indirect taxes unless the recalculation is triggered by a specific condition. Indirect taxes are recalculated when transactions are posted in the following forms:</p>
<ul>
<li><p><strong>Purchase order</strong></p></li>
<li><p><strong>Vendor invoice</strong>–PO and Non PO lines</p></li>
<li><p><strong>Purchase requisitions</strong></p></li>
<li><p><strong>Invoice journal</strong></p></li>
<li><p><strong>Invoice register</strong></p></li>
<li><p><strong>Invoice approval journal</strong></p></li>
<li><p><strong>General journal</strong></p></li>
<li><p><strong>Vendor</strong> <strong>Payment journal</strong></p></li>
<li><p><strong>Customer</strong> <strong>Payment journal</strong></p></li>
<li><p><strong>Free text invoice</strong></p></li>
</ul>
<p>For more information, see <a href="ind-about-recalculation-of-indirect-taxes.md">(IND) About recalculation of indirect taxes</a>.</p></td>
</tr>
<tr class="odd">
<td><p>EXIM DFIA incentive scheme</p></td>
<td><p>The DFIA incentive scheme allows the duty-free import of goods that are used in the manufacture of products for export, or that are used or consumed during the manufacturing process. The DFIA is administered by the office of the DGFT and was originally named the Duty Free Replenishment Certificate. The DFIA helps export companies maintain accurate records of items that can be imported duty-free, based on the incentive scheme and the SION table.</p>
<p>For more information, see <a href="ind-about-the-exim-duty-free-import-authorization-dfia-incentive-scheme.md">(IND) About the EXIM Duty Free Import Authorization (DFIA) incentive scheme</a>.</p></td>
</tr>
<tr class="even">
<td><p>Update tax information in a corrective free text invoice.</p></td>
<td><p>You can define the maximum retail price per unit for an item in the <strong>Free text invoice</strong> form and calculate the tax based on the amount per unit. When excise transactions from the free text invoice are posted, part I of the excise registers is updated with the quantity details.</p>
<p>You can correct a free text invoice that has been posted. For India, you can also update the following tax information in the invoice:</p>
<ul>
<li><p>Update excise registers with details of corrected invoices or canceled invoices.</p></li>
<li><p>Reverse service tax entries when the invoice correction is performed for a settled invoice.</p></li>
<li><p>Reverse TCS entries when the invoice correction is performed after the TCS on an original invoice is settled.</p></li>
</ul>
<p>For more information, see <a href="ind-about-the-exim-duty-free-import-authorization-dfia-incentive-scheme.md">(IND) About the EXIM Duty Free Import Authorization (DFIA) incentive scheme</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Tax rate enhancements for India</p></td>
<td><p>You can enter tax rates that contain five decimal places to calculate amounts for customs, excise, or VAT. The tax rate identifies a tax that is associated with a sale, such as a sales tax, fee, duty, purchase duty, or packing duty. You can enter these rates in the following fields:</p>
<ul>
<li><p><strong>Concessional value</strong> – The concessional value that is defined for Small scale industry (SSI) vendors.</p></li>
<li><p><strong>Preferential value</strong> – The preferential value for tax codes.</p></li>
<li><p><strong>Retention %</strong> – The VAT retention rate for the transaction.</p></li>
<li><p><strong>Percentage</strong> – The VAT retention percentage that is applied to the transaction.</p></li>
<li><p><strong>Tax pct.</strong> – The tax percentage that is used to calculate the customs duty.</p></li>
</ul>
<p>For more information, see <a href="ind-set-up-excise-tax-codes.md">(IND) Set up excise tax codes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements for sales orders and purchase orders enhancements for India</p></td>
<td><p>You can create a purchase order line that has a negative quantity for a non-inventoried item in a new or existing purchase order. You can also create and post a sales return order for a non-inventoried item. You can calculate only the indirect taxes on negative purchase order or sales order lines.</p>
<p>You can correct the quantity and tax amount in a purchase order or a sales order packing slip for which the excise register is already updated. You can correct the invoice before posting. When you post the invoice, the excise register is updated with three register IDs:</p>
<ul>
<li><p>Original quantity and tax amount</p></li>
<li><p>Reversed quantity and tax amount</p></li>
<li><p>Corrected quantity and tax amount</p></li>
</ul>
<p>For more information, see <a href="ind-create-and-post-a-purchase-order-line-with-a-negative-quantity-for-an-item-that-is-not-inventoried.md">(IND) Create and post a purchase order line with a negative quantity for an item that is not inventoried</a> and <a href="ind-correct-a-purchase-order-packing-slip-before-posting-an-invoice.md">(IND) Correct a purchase order packing slip before posting an invoice</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Assign financial dimensions to entries that are generated in the <strong>Transfer orders</strong> form.</p></td>
<td><p>You can assign financial dimensions to each line entry that is generated for transfer orders.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj677831(v=ax.60)">(IND) Transfer orders (modified form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generation of financial statements in for India</p></td>
<td><p>You can generate financial statements, such as balance sheets and profit and loss statements, in Excel. The financial statement report that is generated displays the schedule number column, header notes, and footer notes.</p>
<p>For more information, see <a href="use-microsoft-excel-to-import-and-export-data.md">Use Microsoft Excel to import and export data</a>.</p></td>
</tr>
<tr class="odd">
<td><p>SLJL impact on the functionality for Indian custom duty</p></td>
<td><p>The subledger accounting distribution framework affects the functionality for custom duty. The functionality that is affected, includes the functionality for the following export incentive schemes:</p>
<ul>
<li><p>Advance Authorization (AA)</p></li>
<li><p>Duty Free Import Authorization (DFIA)</p></li>
<li><p>Duty Entitlement Pass book (DEPB)</p></li>
<li><p>Export promotion and Capital Goods (EPCG)</p></li>
</ul>
<p>The subledger accounting distribution framework lets users obtain an overview of the distribution on cost centers before an amount is posted to ledger accounts.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="about-accounting-distributions-and-subledger-journal-entries-for-vendor-invoices.md">About accounting distributions and subledger journal entries for vendor invoices</a></p></li>
<li><p><a href="about-accounting-distributions-and-subledger-journal-entries-for-purchase-orders.md">About accounting distributions and subledger journal entries for purchase orders</a></p></li>
<li><p><a href="about-accounting-distributions-and-subledger-journal-entries-for-free-text-invoices.md">About accounting distributions and subledger journal entries for free text invoices</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Implementation of a cache for withholding tax calculation</p></td>
<td><p>The purpose of this feature is to improve the implementation of the uncommitted tax calculation. A cache for withholding tax is implemented for all transactions from subledger journals, such as invoices, free text invoices, vendor invoices, and purchase orders.</p>
<p>Posting a transaction affects tax recalculation. Therefore, whenever a transaction for TDS or TCS is posted from a source document, the tax is recalculated.</p>
<p>To improve performance and guarantee correct uptake of the subledger journal functionality, tax is not recalculated unless there is a specific triggering event, such as a change to a tax group.</p></td>
</tr>
<tr class="odd">
<td><p>Global address book for India</p></td>
<td><p>The global address book is a centralized location that contains information for business entities, such as customers, vendors, and companies. Tax information and the tax registration number that is attached to these business entities are also retrieved from the global address book.</p>
<p>When you create a new sales order, purchase requisition, purchase order, payment invoice, or payment journal, or when you make stock transaction transfers, the sales tax, VAT, and service tax information is updated from the global address book.</p>
<p>The name that is defined for the primary address in the <strong>Legal entities</strong> form is displayed on the <strong>Tax information</strong> tab for customers and vendors.</p>
<p>For more information, see <a href="global-address-book-overview.md">Global address book overview</a>.</p></td>
</tr>
<tr class="even">
<td><p>Improvements to tax registration number assignments</p></td>
<td><p>For companies in India, the following improvements have been made to the method that is used to assign tax registration numbers:</p>
<ul>
<li><p>Tax information is no longer date effective.</p></li>
<li><p>You can create new tax information records and view existing records for a specific location.</p></li>
<li><p>You can assign the tax information records for specific locations to transactions.</p></li>
<li><p>When you post transactions, registers and accounts are updated with registration numbers for the selected tax information.</p></li>
</ul>
<p>Additionally, changes have been made to the capability to modify registration numbers. In AX 2009, users can directly modify each registration number. Now, when users select the address and then the tax information, the registration numbers are automatically updated.</p>
<p>For more information, see <a href="ind-set-up-tax-registration-numbers.md">(IND) Set up tax registration numbers</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Updates to general ledger and tax inquiry forms</p></td>
<td><p>You can use the <strong>Invoice group</strong> field in the <strong>Indirect tax inquiry</strong> form to filter and list tax transactions for a specific invoice group. You can create queries to view a list of VAT transactions that are posted during a period, based on a specific group.</p>
<p>You can use the <strong>Number sequences</strong> on the <strong>General ledger parameters</strong> form to separate the segments and the ledger accounts.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj856151(v=ax.60)">(IND) Indirect tax inquiry (form)</a> and <a href="https://technet.microsoft.com/library/jj677901(v=ax.60)">(IND) General ledger parameters (modified form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements for the Organizational model for India</p></td>
<td><p>In Microsoft Dynamics AX, you can create organizational structures that align with your business processes or legal entities by using the organizational hierarchy designer. You can create legal entities by using the <strong>Legal entities</strong> form. You can enter address, contact, and tax information for legal entities.</p>
<p>For India, you can enter the tax information for your company on the <strong>Tax registration</strong> tab in the <strong>Manage addresses</strong> form. The address, contact, and tax information is updated in the global address book.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj664569(v=ax.60)">(IND) Legal entities (modified form)</a> and <a href="https://technet.microsoft.com/library/jj664593(v=ax.60)">(IND) Manage addresses (modified form)</a>.</p>
<p>For more information about the Organization model, see the white paper <a href="https://go.microsoft.com/fwlink/?linkid=213125%26clcid=0x409">Implementing and Extending the Organization Model in Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Duties and privileges are added for user roles in features for India.</p></td>
<td><p>In AX 2012 R2, the functionality for role-based security has been added for the following user roles:</p>
<ul>
<li><p>Accountant</p></li>
<li><p>Accounting Manager</p></li>
<li><p>Accounting Supervisor</p></li>
<li><p>Accounts Payable Clerk</p></li>
<li><p>CFO</p></li>
<li><p>Finance Controller</p></li>
<li><p>Materials Manager</p></li>
</ul>
<p>For more information, see <a href="role-based-security-in-microsoft-dynamics-ax.md">Role-based security in Microsoft Dynamics AX</a>.</p></td>
</tr>
<tr class="even">
<td><p>Expanded support for tax types for service industry transactions</p></td>
<td><p>In AX 2012 R2, direct and indirect taxes in India are supported in service management.</p></td>
</tr>
<tr class="odd">
<td><p>View and modify accounting entries before you post them to the general ledger.</p></td>
<td><p>You can view full accounting entries in the <strong>Subledger journal</strong> form. You can modify these entries in the <strong>Accounting distributions</strong> form before you post the entries to the general ledger.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh208685(v=ax.60)">Subledger journal (form)</a> and <a href="https://technet.microsoft.com/library/jj677820(v=ax.60)">(IND) Accounting distributions (modified form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Automatic calculation of TDS when no PAN is registered</p></td>
<td><p>When no PAN is registered for a customer or vendor, the TDS is automatically calculated at a higher rate.</p></td>
</tr>
<tr class="odd">
<td><p>Point of taxation</p></td>
<td><p>For India, you can now select <strong>Point of taxation basis</strong> as the accounting basis for item sales tax groups.</p>
<p>For more information, see <a href="ind-create-item-sales-tax-groups.md">(IND) Create item sales tax groups</a> and <a href="https://technet.microsoft.com/library/jj710918(v=ax.60)">(IND) Item sales tax groups (modified form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>For India customs duty and Export Import Policy (EXIM), if the charge as expense ratio is used, the related customs duty is charged to the expense account.</p></td>
<td><p>The charge as expense is the part of tax that is not allocated to the cost of inventory but is charged to the expense account. You can post the charge as expense tax amount to the import duty expense account by using a separate posting voucher.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to number sequences for Indian financial documents and incentive schemes</p></td>
<td><p>You can set up number sequences based on the data area for ledger vouchers that are generated for EXIM incentive schemes, VAT deferments, withholding tax payments, and shipping bill references. You can also set up number sequences based on the legal entity for the <strong>Goods receipt note</strong> reference.</p>
<p>For more information, see <a href="ind-number-sequences-for-indian-financial-documents.md">(IND) Number sequences for Indian financial documents</a>.</p></td>
</tr>
<tr class="even">
<td><p>Expanded support for tax types for project transactions, billing processes, and tax settlements</p></td>
<td><p>Microsoft Dynamics AX 2012 now supports more tax types to make Project management and accounting comply with the regulatory requirements of India. The scope of this support also extends to the Professional Services Automation add-in (Project III).</p>
<p>The following additional tax types are now supported:</p>
<ul>
<li><p>Service tax</p></li>
<li><p>VAT</p></li>
<li><p>India sales tax</p></li>
<li><p>Excise tax</p></li>
<li><p>Customs</p></li>
<li><p>TDS</p></li>
<li><p>TCS</p></li>
</ul>
<p>Support for the correct calculation of India taxes in Project management and accounting is integrated for primary documents such as purchase orders, purchase requisitions, and requests for quotation, and also for adjustments. You can adjust transactions that have been posted that have incorrect tax groups.</p>
<p>You can view tax calculations that are specific to each transaction line from the <strong>Invoice proposal</strong> form before you bill the customer.</p>
<p>You can enable an option to split invoice proposals based on the tax registration numbers that are included in them and print the project invoice that is specific to each legal entity.</p>
<p>In inquiry forms, you can now filter by project and category. Therefore, it is easier to create some reports that are more frequently required in Indian business scenarios.</p>
<div class="alert">

> [!NOTE]
> <P>This feature extends the support for India tax regulations that was introduced in AX 2009 to AX 2012.</P>


</div>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj677991(v=ax.60)">(IND) Project management and accounting parameters (modified form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>EXIM AA incentive scheme</p></td>
<td><p>The AA is an incentive scheme that is issued by the DGFT. The scheme allows duty-free imports of materials that are required for the manufacture of products for export. The authorizations for the import of raw materials can be granted to a manufacturer exporter or a merchant exporter. Because the raw materials must be imported before the export of final products, these authorizations are called Advance Authorizations. You can apply for an AA license based on confirmed orders (pre-export).</p>
<p>The AA imposes an obligation to use the materials that are imported duty-free to manufacture and export the specified export products. The AA document contains a description, value, and quantity of each authorized item, and the value of the exported items.</p>
<p>For more information, see <a href="ind-about-the-exim-advance-authorization-aa-incentive-scheme.md">(IND) About the EXIM Advance Authorization (AA) incentive scheme</a> and <a href="ind-setting-up-the-exim-advance-authorization-aa-incentive-scheme.md">(IND) Setting up the EXIM Advance Authorization (AA) incentive scheme</a>.</p></td>
</tr>
<tr class="even">
<td><p>General ledger updates for India</p></td>
<td><p>You can perform the following tasks in General ledger:</p>
<ul>
<li><p>Print the financial statement that includes the schedule number for the ledger accounts.</p></li>
<li><p>Calculate the depreciation of fixed assets by selecting <strong>Day based</strong> as the type of calendar when you create the fiscal calendar.</p></li>
<li><p>Select the type of exchange rates to calculate the customs duties for import and export transactions.</p></li>
<li><p>Specify financial dimensions for stock transfers.</p></li>
<li><p>View direct and indirect tax transactions together with accounting entries in subledger journals, and distribute the tax amount among the various dimensions.</p></li>
</ul>
<p>For more information, see <a href="ind-setting-up-and-maintaining-general-ledger.md">(IND) Setting up and maintaining General ledger</a>.</p></td>
</tr>
<tr class="odd">
<td><p>EXIM Duty Drawback (DBK) incentive scheme</p></td>
<td><p>DBK is a rebate of duty that is charged on imported materials or excisable materials that are used to manufacture or process goods that are then exported from India. DBK is the sum of the following:</p>
<ul>
<li><p>Customs duty that is paid on imported input goods. This customs duty includes Special Addition Duty (SAD)</p></li>
<li><p>Excise duty that is paid on indigenous input goods</p></li>
<li><p>Duty that is paid on packing material</p></li>
</ul>
<p>If a customs or excise duty is paid for part of the input goods, only that part is eligible for DBK. Input goods that are obtained without payment of customs or excise duty are not eligible for DBK. The DBK rates are for all Industry Rates, Brand Rate, and Special Brand Rate.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="ind-about-exim-duty-drawback-dbk-incentive-schemes.md">(IND) About EXIM duty drawback (DBK) incentive schemes</a></p></li>
<li><p><a href="ind-exim-duty-drawback-dbk-incentive-scheme-transactions.md">(IND) EXIM Duty Drawback (DBK) incentive scheme transactions</a></p></li>
<li><p><a href="ind-setting-up-the-exim-duty-drawback-dbk-incentive-scheme.md">(IND) Setting up the EXIM Duty Drawback (DBK) incentive scheme</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>VAT commodity codes on sales invoices</p></td>
<td><p>You can print group commodity codes and state commodity codes for each item on sales invoices. If the commodity code is not displayed on sales invoices, the sales tax department charges a higher VAT rate, together with a fine.</p>
<p>For more information, see <a href="ind-create-post-and-print-a-sales-invoice-that-has-a-vat-commodity-code.md">(IND) Create, post, and print a sales invoice that has a VAT commodity code</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Update to the Upgrade toolkit</p></td>
<td><p>This feature guarantees that tax registration numbers that users can enter in Microsoft Dynamics AX 4.0 and AX 2009 for taxable transactions are not lost, and that these numbers are migrated intact to the AX 2012 R2 environment during upgrade.</p></td>
</tr>
<tr class="even">
<td><p>Cancellation of BOE and invoice registration for India</p></td>
<td><p>BOE and invoice registration can now be canceled if the invoice registration has not been updated, and if the related product receipts or invoices have not posted.</p>
<p>For more information, see <a href="ind-cancel-a-bill-of-entry.md">(IND) Cancel a bill of entry</a> and <a href="https://technet.microsoft.com/library/jj874426(v=ax.60)">(IND) Invoice registration (form)</a>.</p></td>
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
<td><p>Apply a reverse charge mechanism for the <strong>Others</strong> category for services.</p></td>
<td><p>You can specify that the category for a service that is provided by vendors or foreign vendors is <strong>Inward</strong>, <strong>Interunit or input</strong>, or <strong>Others</strong>. When you specify a reverse charge for the <strong>Others</strong> service category, the input tax amount is posted to the expense account.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="ind-calculate-service-tax-for-a-purchase-order.md">(IND) Calculate service tax for a purchase order</a></p></li>
<li><p><a href="ind-calculate-service-tax-in-an-invoice-journal-form.md">(IND) Calculate service tax in an Invoice journal form</a></p></li>
<li><p><a href="ind-calculate-service-tax-using-a-vendor-payment-journal.md">(IND) Calculate service tax using a vendor payment journal</a></p></li>
<li><p><a href="ind-post-service-tax-in-purchase-transactions-by-using-the-general-journal-form.md">(IND) Post service tax in purchase transactions by using the General journal form</a></p></li>
<li><p><a href="ind-post-service-tax-in-purchase-transactions-by-using-the-invoice-approval-journal-form.md">(IND) Post service tax in purchase transactions by using the Invoice approval journal form</a></p></li>
<li><p><a href="ind-reverse-charges-for-a-service-receiver-and-a-service-provider.md">(IND) Reverse charges for a service receiver and a service provider</a></p></li>
<li><p><a href="ind-calculate-service-tax-for-a-foreign-vendor.md">(IND) Calculate service tax for a foreign vendor</a></p></li>
<li><p><a href="ind-post-service-tax-in-purchase-transactions-by-using-a-purchase-journal.md">(IND) Post service tax in purchase transactions by using a Purchase journal</a></p></li>
<li><p><a href="ind-specify-a-service-category-for-promissory-notes.md">(IND) Specify a service category for promissory notes</a></p></li>
<li><p><a href="ind-post-service-tax-in-purchase-transactions-by-using-the-invoice-register-form.md">(IND) Post service tax in purchase transactions by using the Invoice register form</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Accounting codes for service tax payments</p></td>
<td><p>You can define accounting codes for service codes. When you select a service code for a transaction, the accounting code that is related to the service code is automatically updated for the transaction. You can also generate a service tax payable report that contains the sales tax payable information for each accounting code.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="ind-calculate-service-tax-for-a-purchase-order.md">(IND) Calculate service tax for a purchase order</a></p></li>
<li><p><a href="ind-calculate-service-tax-in-an-invoice-journal-form.md">(IND) Calculate service tax in an Invoice journal form</a></p></li>
<li><p><a href="ind-calculate-service-tax-using-a-vendor-payment-journal.md">(IND) Calculate service tax using a vendor payment journal</a></p></li>
<li><p><a href="ind-post-service-tax-in-purchase-transactions-by-using-the-general-journal-form.md">(IND) Post service tax in purchase transactions by using the General journal form</a></p></li>
<li><p><a href="ind-post-service-tax-in-purchase-transactions-by-using-the-general-journal-form.md">(IND) Post service tax in purchase transactions by using the General journal form</a></p></li>
<li><p><a href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</a></p></li>
<li><p><a href="ind-post-service-tax-in-purchase-transactions-by-using-the-invoice-register-form.md">(IND) Post service tax in purchase transactions by using the Invoice register form</a></p></li>
<li><p><a href="ind-generate-the-service-tax-payable-report.md">(IND) Generate the service tax payable report</a></p></li>
<li><p><a href="ind-about-accounting-codes-for-services.md">(IND) About accounting codes for services</a></p></li>
<li><p><a href="ind-create-a-tax-setoff-rule-to-settle-an-excise-recoverable-amount.md">(IND) Create a tax setoff rule to settle an excise recoverable amount</a></p></li>
<li><p><a href="ind-calculate-service-tax-for-a-sales-order.md">(IND) Calculate service tax for a sales order</a></p></li>
<li><p><a href="ind-calculate-service-tax-by-using-the-free-text-invoice-form.md">(IND) Calculate service tax by using the Free text invoice form</a></p></li>
<li><p><a href="ind-post-service-tax-transactions-by-using-a-customer-payment-journal.md">(IND) Post service tax transactions by using a customer payment journal</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Calculate withholding tax that excludes taxes and charges.</p></td>
<td><p>A legal entity can calculate withholding tax on rental income in the following ways:</p>
<ul>
<li><p>On the net transaction value that excludes indirect tax</p></li>
<li><p>On the net transaction value that excludes charges</p></li>
<li><p>On the net transaction value that excludes indirect tax and charges</p></li>
<li><p>On the gross transaction value that includes indirect tax</p></li>
<li><p>On the gross transaction value that includes taxes and charges</p></li>
</ul>
<p>For more information, see <a href="ind-configure-withholding-tax-calculation.md">(IND) Configure withholding tax calculation</a> and <a href="ind-withholding-tax-calculation.md">(IND) Withholding tax calculation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Specify the large taxpayer unit (LTU) code for a legal entity.</p></td>
<td><p>You can specify the LTU location code for your legal entity if your legal entity qualifies as a large taxpayer. The LTU code is printed on customer invoices that the legal entity generates and is used to file tax returns.</p>
<p>For more information, see <a href="ind-key-tasks-tax-information-for-legal-entities.md">(IND) Key tasks: Tax information for legal entities</a>.</p></td>
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
<td><p>Tax thresholds and tax concession certificates for India</p></td>
<td><p>You can set up and apply threshold limits on customer and vendor transactions. You can set up threshold limits for direct taxes in India and then specify the tax rates for each threshold limit. You can also set up a tax concession certificate for a customer or a vendor. Microsoft Dynamics AX calculates direct taxes on transactions, based on the threshold segments that you specify. You can apply the following types of threshold limits on transactions:</p>
<ul>
<li><p><strong>Cumulative threshold</strong> – The maximum limit of a cumulative transaction value, beyond which direct tax on the transaction value is applied.</p></li>
<li><p><strong>Transaction threshold</strong> – The maximum limit of an individual transaction value, beyond which direct tax on the transaction value is applied.</p></li>
<li><p><strong>Transaction line threshold</strong> – The maximum limit of a transaction line value, beyond which direct tax on the transaction line value is applied.</p></li>
</ul>
<p>Follow these steps to set up and use threshold limits:</p>
<ol>
<li><p>Set up threshold limits by setting up a threshold definition and designing a threshold hierarchy.</p></li>
<li><p>Assign thresholds to a withholding tax code, and set up tax values to apply to the final level of each threshold segment in the threshold hierarchy.</p></li>
<li><p>Set up a tax concession certificate for a customer or a vendor, if a certificate is required.</p></li>
<li><p>Set up a withholding tax group that contains the withholding tax code to which you assigned the threshold and the threshold values.</p></li>
<li><p>Create and post transactions that use the withholding tax group for the withholding tax code to which you assigned the threshold and threshold values.</p></li>
</ol>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="ind-set-up-threshold-limits.md">(IND) Set up threshold limits</a></p></li>
<li><p><a href="ind-set-up-thresholds-and-concession-certificates-for-tax-calculations.md">(IND) Set up thresholds and concession certificates for tax calculations</a></p></li>
<li><p><a href="ind-tax-thresholds-and-tax-concession-certificates.md">(IND) Tax thresholds and tax concession certificates</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Use the sales tax hierarchy to process sales tax settlements, sales tax payments, and sales tax returns.</p></td>
<td><p>You can use the sales tax hierarchy to set off taxes, and you can then generate reports. A sales tax hierarchy is a hierarchical structure that can contain multiple levels of various components, such as service codes, tax codes, and tax components. You can set up a sales tax hierarchy based on your business requirements, and then use this sales tax hierarchy to process sales tax settlements, sales tax payments, and sales tax returns.</p>
<p>Follow these steps to set up and use the sales tax hierarchy:</p>
<ol>
<li><p>Set up the parameter to use the sales tax hierarchy.</p></li>
<li><p>Set up a sales tax hierarchy, based on the structure of the hierarchy. You can maintain multiple versions of the sales tax hierarchy. The levels of the hierarchy are determined by the structure. For example, a sales tax hierarchy that is used to set off excise duty has three levels: tax type, tax component, and tax record type. To modify the structure based on your business requirements, you can use the sales tax hierarchy framework.</p></li>
<li><p>Set up and maintain a sales tax hierarchy profile. You can create multiple hierarchy profiles and versions that are set off based on your business requirements.</p></li>
<li><p>Create a tax setoff rule that is used to set off the output tax by using the input tax.</p></li>
<li><p>Settle a sales tax transaction by using the sales tax hierarchy, and then generate a sales tax payment.</p></li>
</ol>
<p>You can view the details of the settled taxes for each tax component in the <strong>Payment journal</strong> form.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="ind-sales-tax-hierarchies.md">(IND) Sales tax hierarchies</a></p></li>
<li><p><a href="ind-set-up-and-use-a-sales-tax-hierarchy.md">(IND) Set up and use a sales tax hierarchy</a></p></li>
</ul></td>
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
<td><p>Calculate assessable value and customs duty for an import order in Indian rupees.</p></td>
<td><p>You can calculate assessable value and then calculate customs duty for an import purchase order in Indian rupees. The calculations of assessable value and customs duty are based on exchange rates.</p>
<p>For more information, see <a href="ind-calculate-customs-duty-for-an-import-purchase-order.md">(IND) Calculate customs duty for an import purchase order</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate and print an excise invoice for goods.</p></td>
<td><p>You can generate and print an excise invoice for goods that are transported from a factory or warehouse by using a sales order, stock transfer order, or purchase return order. You can also calculate excise duty and print an excise invoice for a stock transfer order.</p>
<p>For more information, see <a href="ind-generate-and-print-an-excise-invoice-for-goods.md">(IND) Generate and print an excise invoice for goods</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Manage the gate entry and exit of goods.</p></td>
<td><p>You can manage the gate entry and exit of goods.</p>
<p>For more information, see <a href="ind-manage-gate-entry-and-exit-of-goods.md">(IND) Manage gate entry and exit of goods</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate annexure 58 for returned items.</p></td>
<td><p>You can generate and print annexure 58 for goods that are returned by customers for repair. You can then dispatch the returned goods back to customer.</p>
<p>For more information, see <a href="ind-generate-annexure-58-for-returned-items.md">(IND) Generate annexure 58 for returned items</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Update excise registers for finished goods.</p></td>
<td><p>You can generate and print an excise invoice for goods that are transported from a factory or a warehouse by using a sales order, transfer order, or purchase return order. You can also update the DSA and excise registers for finished goods, damaged goods, expired goods, and by-products.</p>
<p>For more information, see <a href="ind-update-excise-registers-for-finished-goods-and-by-products.md">(IND) Update excise registers for finished goods and by-products</a>.</p></td>
</tr>
<tr class="even">
<td><p>Accrue payable service tax.</p></td>
<td><p>You can set up Microsoft Dynamics AX to accrue payable service tax when an invoice is posted in the reverse charge mechanism.</p>
<p>For more information, see <a href="ind-calculate-reverse-charges-on-service-tax.md">(IND) Calculate reverse charges on service tax</a>.</p></td>
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
<td><p>Asset depreciation calculation</p></td>
<td><p>Under India Companies Act 2013, depreciation is required to calculate the useful life of an asset regardless of the method of depreciation already used. Updates are included in this release to address component accounting and shift depreciation calculation.</p></td>
</tr>
<tr class="even">
<td><p>Exchange rate on import of service for service tax and TDS</p></td>
<td><p>When you import services from overseas and the invoice is issued before payment, the payable service tax is expected to be converted using the GAAP rate on the payment date. For TDS, the TT rate is used instead of the GAAP rate.</p></td>
</tr>
<tr class="odd">
<td><p>e-TDS/e-TCS Return validation from FVU tool 4.5</p></td>
<td><p>Electronic reports are now compliant with the File validation utility (FVU) version 4.5 tool. In the <strong>Vendor</strong> and <strong>Customer</strong> forms, on the <strong>Tax details</strong> tab, if the PAN status is <strong>Not Available</strong>, <strong>Applied</strong>, or <strong>Not valid</strong>, the <strong>Reference number</strong> field is enabled so that you can enter the reference number needed by the FVU 4.5 tool.</p></td>
</tr>
<tr class="even">
<td><p>RG23D requirements for purchase, import, and stock transfer invoices are reference in sales invoices</p></td>
<td><p>The functionality that is included for the RG23D requirement regarding invoice references in sales invoices, covers end-to-end scenarios of the sale of goods. These scenarios include, for example, from importer to first stage dealer, first stage to second stage dealer, first stage to manufacturer, second stage to manufacture, second stage to end consumer, and second stage to dealer. This functionality also covers the import scenario where the Special additional duty of custom (SAD) may be passed on to the corresponding posting accounting.</p></td>
</tr>
<tr class="odd">
<td><p>Assessable values on returned goods and quarterly dealer returns</p></td>
<td><p>You can now set a default assessable value on returned goods on the purchase return order line, and read the assessable value from the posted purchase order line against which a return order is created for returned goods. The assessable value for the quantity being returned through the return order is calculated and used as the default assessable value on the return order line. The quarterly return for the traders report displays outward transactions and the corresponding inward transactions.</p></td>
</tr>
<tr class="even">
<td><p>Apply excise on service tax to transfer service tax to the CENVAT credit account</p></td>
<td><p>The tax register balance dynamic view functionality is extended to show utilized and adjusted CENVAT credit (RG23 A/C) against service tax liability and other taxes. The view also shows utilized and adjusted service tax credit against excise liability and other taxes extended in the new <strong>Service tax register balance</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p>Deferred excise on capital goods</p></td>
<td><p>You can now reverse deferred excise credit to a CENVAT credit account in the next period while tracking the original transaction. You can also avail 100 percent of the CENVAT credit if capital goods are removed in the year of purchase, if one of the following conditions are met:</p>
<ul>
<li><p>Capital goods are removed in good condition.</p></li>
<li><p>Capital goods are removed as write-off.</p></li>
<li><p>Capital goods are removed as waste/scrap.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Excise credit utilization on receipt of goods</p></td>
<td><p>New functionality for the excise credit utilization on receipt of goods enables users to do the following:</p>
<ul>
<li><p>Claim CENVAT credit after posting the product receipt.</p></li>
<li><p>Adjust excise duty tax adjustment at the product receipt stage.</p></li>
<li><p>Update RG 23A Part II immediately after posting the product receipt.</p></li>
<li><p>Block excise duty tax adjustment when invoicing CENVAT credit during the product receipt stage.</p></li>
<li><p>Use the CENVAT credit during the sales tax payment process.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Rate under notifications</p></td>
<td><p>You can now record and print the following information on <strong>Sales excise invoice</strong> reports: notification numbers and dates, serial numbers, effective dates of notifications, and the expiry date of notifications.</p></td>
</tr>
<tr class="even">
<td><p>Excise registers and reports</p></td>
<td><p>The following statutory excise registers and reports have been added:</p>
<ul>
<li><p>Purchase and Sales Register</p></li>
<li><p>CENVAT credit utilization (debit) report</p></li>
<li><p>Inter Unit transaction register inquiry</p></li>
<li><p>Personal ledger account</p></li>
<li><p>Sample register</p></li>
<li><p>Daily stock account register</p></li>
<li><p>RG23 A Part I</p></li>
<li><p>RG23 C Part I</p></li>
<li><p>RG23 A Part II</p></li>
<li><p>RG23 C Part II</p></li>
</ul>
<p>Maintenance of these reports is typically required for all manufacturers. These reports are in addition to the comprehensive excise inquires where users can configure their own reports.</p></td>
</tr>
</tbody>
</table>

  


