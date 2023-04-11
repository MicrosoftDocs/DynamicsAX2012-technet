---
title: "What's new: Sales tax processing"
TOCTitle: Sales tax processing
ms:assetid: d25a2392-a067-4109-a6c8-c9b286f50c09
ms:mtpsurl: https://technet.microsoft.com/library/Dn527247(v=AX.60)
ms:contentKeyID: 59623375
author: tonyafehr
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Sales tax processing 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sales tax processing in Microsoft Dynamics AX 2012 has been updated to help organizations comply with applicable tax laws in many countries/regions. These tax laws include the European Union’s 2010 regulations about value-added tax (VAT) for services. Reporting for the European Union (EU) sales list has been updated to comply with these changes. Tax rates can now have up to five decimal places. Changes to calculated taxes for selected source documents are now saved before the source document is journalized. Changes to calculated taxes for selected journals are now saved before the journal entries are posted.

For more information about taxes in AX 2012, see the white papers [Implementing the Tax Framework for Microsoft Dynamics AX 2012](https://download.microsoft.com/download/7/c/d/7cdddc76-0e08-4240-8c51-ece6142255c9/implementing+the+tax+framework_ax2012.pdf) and [Implementing the Account and Financial Dimensions Framework for Microsoft Dynamics AX 2012 Applications](https://go.microsoft.com/fwlink/?linkid=213133).

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
<td><p>Journals:</p>
<ul>
<li><p>General journal</p></li>
<li><p>Invoice journal</p></li>
<li><p>Invoice register</p></li>
<li><p>Invoice approval journal</p></li>
<li><p>Promissory note journals</p></li>
<li><p>Bill of exchange journals</p></li>
<li><p>Project expense journal</p></li>
</ul>
<p>Source documents:</p>
<ul>
<li><p>Customer invoices</p></li>
<li><p>Free text invoices</p></li>
<li><p>Purchase requisitions</p></li>
<li><p>Purchase orders</p></li>
<li><p>Product receipts</p></li>
<li><p>Project invoices</p></li>
<li><p>Travel expense reports</p></li>
<li><p>Vendor invoices</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Tax rates that contain up to five decimal places can be used.

On January 1, 2010, changes to the rules that govern the place of supply of services took effect. These changes also affect the simplified compliance requirements for EU businesses that provide VAT-taxable services in multiple EU member states.

Changes to EU sales list reporting provide more detailed reporting by item, service, or investment amounts.

## Special considerations

You must understand how the sales tax functionality in Microsoft Dynamics AX works. For more information, see [Setting up sales tax codes](setting-up-sales-tax-codes.md) and [Setting up sales tax](setting-up-sales-tax.md).

## Comparison with Microsoft Dynamics AX 2009

Taxes have changed considerably since AX 2009. AX 2012 includes changes to the following areas:

  - Decimal places in tax rates for sales tax codes

  - Saving calculated taxes before source documents or journals are posted

  - VAT package for services

  - Reporting for EU sales list transfer functions

## Decimal places in tax rates for sales tax codes

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
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use more than two decimal places for tax rates.</p></td>
<td><p>Tax rates that contain three or more decimal places, such as 0.125, were rounded to two decimal places, such as 0.13.</p></td>
<td><p>Tax rates can contain up to five decimal places.</p></td>
<td><p>This change helps organizations comply with local, state, and federal requirements in various countries/regions.</p></td>
</tr>
</tbody>
</table>


## Saving calculated taxes before source documents or journals are posted

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
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Modify and save calculated tax amounts for the following source documents:</p>
<ul>
<li><p>Free text invoice</p></li>
<li><p>Purchase requisition</p></li>
<li><p>Purchase order</p></li>
<li><p>Product receipt</p></li>
<li><p>Vendor invoice</p></li>
<li><p>Travel expense report</p></li>
</ul></td>
<td><p>Taxes were recalculated every time that a source document was opened, and changes were not saved until the source document was posted (journalized).</p></td>
<td><p>You can change the calculated taxes for a source document, and the changes are saved, even if the source document is not immediately journalized.</p>
<p>For vendor invoices, you can use a new parameter to preserve the sales tax information from the vendor, either through a service or through manual entry that is based on a paper invoice from the vendor. Otherwise, the sales tax information that is calculated might override the actual amounts in some cases.</p>
<p>For more information, see <a href="set-up-a-default-tax-profile-for-a-customer-or-vendor.md">Set up a default tax profile for a customer or vendor</a>.</p></td>
<td><p>Usability is improved.</p></td>
</tr>
<tr class="even">
<td><p>Clear sales tax amounts that are saved for a sales tax code or sales tax group.</p></td>
<td><p>Not available</p></td>
<td><p>If this change is required, you can clear the saved tax amounts for a sales tax code, sales tax group, or item sales tax group.</p></td>
<td><p>Usability for organizational compliance with tax regulations is improved.</p></td>
</tr>
<tr class="odd">
<td><p>Optionally hide sales tax amounts in journal entry forms.</p></td>
<td><p>Not available</p></td>
<td><p>For each journal name, you can select whether to hide or show sales tax amounts in journal entry forms.</p></td>
<td><p>Performance is improved.</p></td>
</tr>
</tbody>
</table>


## VAT package for services

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
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up rules that govern the place of supply of services.</p></td>
<td><p>This feature was available as a regulatory feature update for the affected countries/regions.</p></td>
<td><p>Users can set up different item sales tax groups and assign the correct reporting type (item, service, or investment).</p></td>
<td><p>Organizations can more easily comply with EU regulations.</p></td>
</tr>
<tr class="even">
<td><p>Set up EU sales list reports.</p></td>
<td><p>This feature was available as a regulatory feature update for the affected countries/regions.</p></td>
<td><p>Services, investments, and items are listed on EU sales list reports.</p></td>
<td><p>Organizations can more easily comply with EU regulations.</p></td>
</tr>
<tr class="odd">
<td><p>Sell services across country/region borders.</p></td>
<td><p>This feature was available as a regulatory feature update for the affected countries/regions.</p></td>
<td><p>Invoices are processed by using appropriate VAT rates for item and service products.</p></td>
<td><p>Rates are automatically calculated.</p></td>
</tr>
</tbody>
</table>


## Reporting for EU sales list transfer functions

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
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Include line amounts for services.</p></td>
<td><p>Only line amounts that included items could be transferred to the EU sales list.</p></td>
<td><p>Users can include line amounts for lines that use an item sales tax group that has a reporting type of <strong>Service</strong>.</p></td>
<td><p>Organizations can more easily comply with EU regulations.</p></td>
</tr>
<tr class="even">
<td><p>Include line amounts for investments.</p></td>
<td><p>Not available</p></td>
<td><p>Users can include line amounts for lines that use an item sales tax group that has a reporting type of <strong>Investment</strong>.</p></td>
<td><p>Organizations can more easily comply with EU regulations.</p></td>
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
<td><p>Sales taxes and ledger accounts can be reconciled more easily</p></td>
<td><p>In earlier releases of AX 2012, it was difficult to reconcile sales tax amounts with ledger accounts. Now, the <strong>Sales tax specification by ledger account</strong> report includes options that let you sort the report by sales tax code or ledger account, include subtotals by sales tax code, and print only totals or both totals and details.</p>
<p>For more information, see <a href="sales-tax-specification-by-ledger-transaction-report-taxspecperledgertrans.md">Sales tax specification by ledger transaction report (TaxSpecPerLedgerTrans)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Performance is improved for tax reporting</p></td>
<td><p>Performance is improved for the <strong>Sales tax specification by ledger account</strong> (TaxSpecPerLedgerTrans ) report and the <strong>Sales tax list</strong> (TaxList) report.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="sales-tax-list-report-taxlist.md">Sales tax list report (TaxList)</a></p></li>
<li><p><a href="sales-tax-specification-by-ledger-transaction-report-taxspecperledgertrans.md">Sales tax specification by ledger transaction report (TaxSpecPerLedgerTrans)</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Posting of sales tax amounts for intercompany transactions</p></td>
<td><p>When you post an intercompany transaction that includes sales tax amounts, you can select to post the sales tax amount to either the source legal entity or the destination legal entity.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="posting-sales-tax-amounts-for-intercompany-transactions.md">Posting sales tax amounts for intercompany transactions</a></p></li>
<li><p><a href="posting-sales-tax-amounts-for-intercompany-transactions-white-paper.md">Posting sales tax amounts for intercompany transactions (White paper)</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

  


