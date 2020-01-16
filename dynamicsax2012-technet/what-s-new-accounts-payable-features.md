---
title: "What's new: Accounts payable features"
TOCTitle: Accounts payable features
ms:assetid: aaa4e957-c34c-4f42-8b2f-3a1441aef71a
ms:mtpsurl: https://technet.microsoft.com/library/Dn527209(v=AX.60)
ms:contentKeyID: 59623338
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
---

# What's new: Accounts payable features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Accounts payable](accounts-payable.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

## What’s new in AX 2012

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
<td><p>The sign of the invoice quantity must match the sign of the ordered quantity.</p></td>
<td><p>The sign of the invoice quantity on a vendor invoice must match the sign of the ordered quantity on the purchase order. In earlier versions, you could enter a negative invoice quantity to record the return of a product. To provide better accounting control, this functionality is no longer available. Instead, you can issue a credit note for the purchase order line as a separate purchase order line. In other words, you can enter a purchase order line that has a negative quantity.</p>
<p>For more information, see <a href="correct-a-vendor-invoice-that-was-matched-to-the-wrong-product-receipt-line.md">Correct a vendor invoice that was matched to the wrong product receipt line</a>.</p></td>
</tr>
<tr class="even">
<td><p>A unit price that is based on an inventory cost price is updated only one time for a customer invoice.</p></td>
<td><p>The unit price on an intercompany purchase order and an intercompany sales order is updated for changes only when the first customer invoice for the intercompany sales order is entered. The update occurs only if the unit cost price is changed in Inventory management, and this update occurs automatically. If a subsequent customer invoice is entered, the unit price for that customer invoice does not come from the cost of the item. Instead, the unit price comes from the intercompany purchase order.</p>
<p>For more information, see <a href="about-changing-intercompany-orders.md">About changing intercompany orders</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to the Accounts payable invoice table</p></td>
<td><p>In earlier versions, unposted purchase order invoices that were entered in the <strong>Posting invoice</strong> form were stored in the same tables as information about updating purchase orders, receipts lists, and packing slips. In this version, unposted purchase order invoices, which are now known as vendor invoices, are stored in a separate set of tables.</p>
<p>For more information, see <a href="key-tasks-vendor-invoices.md">Key tasks: Vendor invoices</a>.</p></td>
</tr>
<tr class="even">
<td><p>Changes to invoice matching for line items that are identified by descriptions and categories</p></td>
<td><p>You can match an invoice line that is identified by a description and a category to a corresponding purchase order line and product receipt line. This feature is based on the functionality that you use to enter lines that are identified by a description and a category on a purchase order, product receipt, and invoice. Additionally, you can use this feature together with purchasing policies that are assigned to line items that are identified by descriptions and categories.</p>
<p>For more information, see <a href="about-accounts-payable-invoice-matching.md">About Accounts payable invoice matching</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create vendor invoices and credit notes from electronic invoices.</p></td>
<td><p>A new service for Microsoft Dynamics AX Application Integration Framework (AIF), VendVendInvoiceService, creates vendor invoices and credit notes from invoices that are received electronically. The service also lets vendors request and retrieve unposted invoice information in Accounts payable.</p>
<p>For more information, see <a href="about-integration-ports-for-vendor-invoices.md">About integration ports for vendor invoices</a>.</p></td>
</tr>
<tr class="even">
<td><p>In the <strong>Vendor invoice</strong> form, enter vendor invoice lines that are not related to a purchase order.</p></td>
<td><p>You can enter vendor invoice lines in the <strong>Vendor invoice</strong> form, even if the lines are not related to a purchase order. The same vendor invoice can include a combination of lines that are related to purchase orders and lines that are not related to purchase orders. The following lines are examples of vendor invoice lines that are not related to a purchase order:</p>
<ul>
<li><p>Subscription dues</p></li>
<li><p>Conference event registrations</p></li>
<li><p>Catering services</p></li>
<li><p>Cleaning services</p></li>
</ul>
<p>You can enter vendor invoice lines that are not related to a purchase order and do not create inventory transactions. However, inventoried or stocked lines are not supported on vendor invoice lines that are not related to a purchase order.</p>
<p>For more information, see <a href="key-tasks-vendor-invoices.md">Key tasks: Vendor invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Invoice matching: Price total matching</p></td>
<td><p>If the parameter that enables price total matching in the <strong>Accounts payable parameters</strong> form is selected, the net amount of an invoice line plus the net amount of any pending invoice lines and previously posted invoice lines is compared with the purchase order line. If the variance amount in the accounting currency exceeds the tolerance percentage, amount, or percentage and amount for price total matching, the user receives a message that warns about a matching discrepancy. This type of variance can occur when partial invoices individually meet quantity and price tolerances, but when these invoices are combined, they exceed a specified percentage or currency value that is defined by the legal entity. Tolerances for price total matching can be set up per legal entity.</p>
<p>For more information, see <a href="about-accounts-payable-invoice-matching.md">About Accounts payable invoice matching</a> and <a href="set-up-accounts-payable-invoice-matching.md">Set up Accounts payable invoice matching</a>.</p></td>
</tr>
<tr class="even">
<td><p>Invoice matching: Enhancements to charge matching</p></td>
<td><p>If the option to use charges matching is selected in the <strong>Accounts payable parameters</strong> form, charges on a vendor invoice can be compared with the expected charges from the purchase order. If the variance exceeds the tolerance percentage for charges, an indicator is displayed to warn the user about the matching discrepancy. Charge tolerances can be set up per company or for individual charges codes.</p>
<p>For more information, see <a href="about-accounts-payable-invoice-matching.md">About Accounts payable invoice matching</a> and <a href="set-up-accounts-payable-invoice-matching.md">Set up Accounts payable invoice matching</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Invoice matching: Invoice total matching</p></td>
<td><p>Invoice totals on a vendor invoice are compared with the expected totals, based on the purchase order information. If the variance exceeds the tolerance percentage for invoice total matching, an indicator is displayed to warn the user about the matching discrepancy. Tolerances for invoice total matching can be set up per legal entity or for individual vendor.</p>
<p>For more information, see <a href="about-accounts-payable-invoice-matching.md">About Accounts payable invoice matching</a> and <a href="set-up-accounts-payable-invoice-matching.md">Set up Accounts payable invoice matching</a>.</p></td>
</tr>
<tr class="even">
<td><p>Workflow for vendor invoice processing</p></td>
<td><p>By using two new workflow types, <strong>VendProcessInvoice</strong> and <strong>VendProcessInvoiceLine</strong>, users can create user-defined workflows for vendor invoices that are typically entered in the <strong>Vendor invoice</strong> form and other forms that use the InvoiceInfo* tables as the data source. The workflow process operates on data that is imported into the InvoiceInfo* tables, and can be used to model the processing steps for the vendor invoices. The workflow types contain the following elements:</p>
<ul>
<li><p>Approval elements for creating approval tasks</p></li>
<li><p>A task element that is used when vendor invoices are completed and corrected</p></li>
<li><p>Automated tasks that can be run programmatically without user intervention to perform selected validations and post the vendor invoices.</p></li>
</ul>
<p>Validations of vendor invoice, such as matching, are performed programmatically when the workflow is run. The validations use the settings of relevant Accounts payable parameters. Security is used to determine the behavior that is supported while an active workflow instance is associated with the vendor invoice. The standard workflow infrastructure in Microsoft Dynamics AX that lets a user create workflows, that determines the run-time behavior of the associated workflow instances, and that creates workflow history is used.</p>
<p>For more information, see <a href="set-up-vendor-invoice-workflows.md">Set up vendor invoice workflows</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Invoice matching: Two-way and three-way line matching policy</p></td>
<td><p>The line matching policy can be set up as follows:</p>
<ul>
<li><p><strong>Three-way</strong> – Matching compares the invoice, purchase order, and product receipt.</p></li>
<li><p><strong>Two-way</strong> – Matching compares the invoice and purchase order.</p></li>
<li><p><strong>Not required</strong> – Unit price matching and price totals matching are not performed.</p></li>
</ul>
<p>The line matching policy can be set up per legal entity, and also for items, vendors, or combinations of items and vendors.</p>
<p>For more information, see <a href="about-accounts-payable-invoice-matching.md">About Accounts payable invoice matching</a>.</p></td>
</tr>
<tr class="even">
<td><p>Invoice matching task for workflow</p></td>
<td><p>Invoice matching is now available as a workflow task that can be performed without user intervention. The workflow can be started based on a business event in Microsoft Dynamics AX. For example, the workflow can be started when new records are created by using the vendor invoice service. Vendor portal scenarios and import scenarios in which vendor invoices are processed without user intervention are supported. In Microsoft Dynamics AX 2009, invoice matching was performed automatically through the user interface when an invoice was created, modified, or retrieved. The new tasks use the same underlying logic that the user interface uses to perform invoice matching.</p>
<p>For more information, see <a href="set-up-vendor-invoice-workflows.md">Set up vendor invoice workflows</a>.</p></td>
</tr>
<tr class="odd">
<td><p>In the <strong>Vendor invoice</strong> form, enter vendor invoices that are not for a purchase order.</p></td>
<td><p>Invoice header fields have been added to the <strong>Vendor invoice</strong> form, so that you can use this form to enter a category-based invoice line that is not related to a purchase order.</p>
<p>For more information, see <a href="key-tasks-vendor-invoices.md">Key tasks: Vendor invoices</a>.</p></td>
</tr>
<tr class="even">
<td><p>Postdated checks</p></td>
<td><p>You can issue and receive checks that have a check date in the future. These checks are also known as postdated checks. Postdated checks are used as a common business practice in Asia, Africa, and many other parts of the world. Many businesses use checks as the primary way to make and receive payments.</p>
<p>You can create postdated checks in payment journals in both Accounts receivable and Accounts payable. Postdated checks use standard functionality in Microsoft Dynamics AX, such as payment journals, financial dimensions, check printing, centralized payments, settlements, and banking.</p>
<p>Postdated checks are not considered legal in certain parts of the world, such as Southeast Asia, Australia, and New Zealand, but are sometimes still used as a business practice in those countries/regions. To support this business practice but still comply with applicable laws, you can choose whether the check amount is reflected in your accounting books until the maturity date of the check is reached. If financial posting for postdated checks is turned off, the checks are documented for record-keeping purposes, and the financial transaction occurs only when the maturity date of the check is reached.</p>
<p>For more information, see <a href="set-up-postdated-checks.md">Set up postdated checks</a>, and <a href="register-and-post-a-postdated-check-for-a-vendor.md">Register and post a postdated check for a vendor</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Improved forms for creating and posting invoices</p></td>
<td><p>The forms for creating and posting invoices are easier to understand and use, and you can now enter all the required information in one form. For more information, see <a href="https://technet.microsoft.com/library/hh209644(v=ax.60)">Vendor invoice (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Verify the receipt of W-9 forms from vendors.</p></td>
<td><p>Before you post a document, you can verify whether a vendor has provided a W-9 form. If the vendor has not provided a W-9 form, you can hold the document while you wait for the form from the vendor.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/aa596348(v=ax.60)">Accounts payable parameters (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Advance payments on vendor invoices</p></td>
<td><p>When you have to pay a vendor before goods are delivered or a service is performed, you can create a vendor invoice line that includes a category and the amount that must be paid in advance. You can validate the amount of the advance payment that is listed on the vendor invoice against the amount that is listed on the purchase order. You can also apply the vendor invoice for the advance payment against the vendor invoice for the items or service.</p>
<p>For more information, see <a href="prepay-for-product-or-service-overview.md">Prepay for product or service overview</a>.</p></td>
</tr>
<tr class="even">
<td><p>Vendor self-service</p></td>
<td><p>Vendors can create and modify their invoices directly from the vendor self-service portal in Enterprise Portal for Microsoft Dynamics AX. Vendors can create an invoice from a purchase order, or they can create an invoice and add a purchase order to it.</p>
<p>For more information, see <a href="create-or-maintain-your-vendor-invoices.md">Create or maintain your vendor invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Add open purchase orders and purchase order lines to an invoice.</p></td>
<td><p>You can use the <strong>Retrieve purchase orders</strong> form to create one invoice for selected purchase orders and purchase order lines. In a list in the <strong>Retrieve purchase orders</strong> form, you can select the open purchase orders and lines to combine on the same invoice.</p>
<p>For more information, see <a href="key-tasks-vendor-invoices.md">Key tasks: Vendor invoices</a> and <a href="https://technet.microsoft.com/library/hh209504(v=ax.60)">Retrieve purchase orders (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Improved forms for creating and posting invoices, purchase orders, receipt lists, and packing slips</p></td>
<td><p>The forms for creating and posting invoices, purchase orders, receipt lists, and packing slips are easier to understand and use. For each document type, you can now enter all the required information in one form. For more information, see <a href="https://technet.microsoft.com/library/hh209644(v=ax.60)">Vendor invoice (form)</a> and <a href="https://technet.microsoft.com/library/aa587152(v=ax.60)">Purchase posting (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create payment invoice groups, and pay a group of invoices by using the same payment.</p></td>
<td><p>You can group invoices by a common code. Then, if one invoice in the payment group is paid, the other invoices in the group are included in the same payment.</p>
<p>For more information, see <a href="add-invoices-to-payment-groups.md">Add invoices to payment groups</a>.</p></td>
</tr>
<tr class="even">
<td><p>Print copies of payments as nonnegotiable checks.</p></td>
<td><p>You can print copies of payments, such as checks, promissory notes, and electronic payments. The copies are printed as nonnegotiable checks.</p>
<p>For more information, see <a href="print-copies-of-payments-as-non-negotiable-checks.md">Print copies of payments as non-negotiable checks</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Set up prenotes to validate customer and vendor bank accounts for electronic funds transfer (EFT).</p></td>
<td><p>You can now set up prenotes for customer and vendor bank accounts for EFT. For electronic payments, banks use prenotes to verify the accuracy of account data, such as routing numbers and account numbers.</p>
<p>For more information, see <a href="set-up-prenotes.md">Set up prenotes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Put Accounts payable payments on hold.</p></td>
<td><p>You can put Accounts payable payments on hold until a specified release date. You can also put these payments on hold indefinitely by leaving the release date blank. You can use holds to stop Accounts payable payments either by holding all payments for a vendor or by holding the payment of a selected invoice. When you put a payment on hold, you can prevent an approved invoice from generating a payment until the release date, if a release date is specified.</p>
<p>For more information, see <a href="place-an-accounts-payable-payment-on-hold.md">Place an Accounts payable payment on hold</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Organize invoices into groups to simplify retrieval and handling.</p></td>
<td><p>You can now group invoices by a common code, so that you do not have to use an exact query to retrieve a set of similar invoices. After you have retrieved the invoice group, you can easily post all the invoices at the same time.</p>
<p>For more information, see <a href="add-invoices-to-invoice-groups.md">Add invoices to invoice groups</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create a confirming purchase order for unplanned vendor purchases (Public sector).</p></td>
<td><p>In an emergency or special circumstance, you can create an order that circumvents the usual purchasing process. For example, you can authorize an order that has only a purchase order number instead of a printed purchase order document. You can use the <strong>Confirming PO code</strong> field to track these unplanned purchases.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh208558(v=ax.60)">Confirming PO codes (form) (Public sector)</a></p></td>
</tr>
<tr class="odd">
<td><p>Select among multiple remittance addresses.</p></td>
<td><p>You can select among multiple remittance addresses for your organization. You can use a default remittance address for specific invoices, or you can use a different address that you selected for an invoice or a payment.</p></td>
</tr>
<tr class="even">
<td><p>Create invoices from the vendor self-service portal.</p></td>
<td><p>Vendors can create and modify their invoices directly from the vendor self-service portal in Enterprise Portal. Vendors can create an invoice from a purchase order or packing slip, or they can create an invoice and add a purchase order to it.</p>
<p>For more information, see <a href="create-or-maintain-your-vendor-invoices.md">Create or maintain your vendor invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Transfer encumbrance entries for purchase orders from the closing fiscal year to the new fiscal year.</p></td>
<td><p>If you encumber purchase orders, you can process year-end closing entries to the general ledger and against budget reserves at the end of each fiscal year. When a new fiscal year is created, a new set of adjusting entries is made to correctly reflect the encumbrances in the new fiscal year. These entries guarantee that the purchase orders are correctly represented on the year-end financial statements.</p>
<p>For more information, see <a href="process-purchase-orders-at-year-end.md">Process purchase orders at year end</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create flexible rules for vendor invoices.</p></td>
<td><p>Business rules for vendor invoices are now more flexible. You can enforce your business rules across all operating legal entities, but still allow for local variations that are based on criteria such as currency and country/region.</p>
<p>For more information, see <a href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</a>.</p></td>
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
<td><p>Adjust taxes on an invoice line.</p></td>
<td><p>You can adjust the taxes that are calculated on an invoice line before you post the invoice.</p>
<p>For more information, see <a href="revise-the-sales-tax-amount-on-a-transaction-before-posting.md">Revise the sales tax amount on a transaction before posting</a>.</p></td>
</tr>
<tr class="even">
<td><p>Integrate a payment calendar to control due dates for payments.</p></td>
<td><p>New functionality for a payment calendar in the Accounts receivable and Accounts payable areas replaces similar functionality that was previously available only for certain countries/regions. When the payment calendar is used together with rules for due dates, companies can specify non-business days for countries and regions, and additional holidays at the state and province levels. Companies can also specify non-business days for any other purpose, such as non-banking days. This functionality helps guarantee that due dates for payments on vendor and customer invoices are not set for non-business days. When a payment is due on a non-business day, the new due date control moves the date to the nearest business day either before or after the default date, based on options that you select.</p>
<p>You can also use the due date control together with the payment calendar to make sure that calculations of grace periods for interest and fees for payments start on the nearest business day. This functionality can be used, for example, to enhance the due date and payment date control in Accounts payable. You can then avoid any unplanned interest or fees for late vendor payments. Additionally, payment processing is easier, because due dates are always on a processing day.</p>
<p>For more information, see <a href="about-payment-calendars.md">About payment calendars</a>.</p></td>
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
<td><p>Generate positive pay files to help banks prevent check fraud.</p></td>
<td><p>Set up positive pay to generate an electronic list of checks every time that checks are printed. When a check is presented to the bank, the bank compares the check with the list of checks that was previously submitted. If the check matches a check in the list, the bank clears the check. If the check does not match a check in the list, the bank holds the check for review.</p>
<p>Positive pay is also known as SafePay.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="set-up-positive-pay.md">Set up positive pay</a></p></li>
<li><p><a href="generate-and-print-vendor-checks.md">Generate and print vendor checks</a></p></li>
<li><p><a href="issue-worker-payments.md">Issue worker payments</a></p></li>
<li><p><a href="create-a-positive-pay-file-for-multiple-legal-entities-and-bank-accounts.md">Create a positive pay file for multiple legal entities and bank accounts</a></p></li>
<li><p><a href="void-unposted-checks.md">Void unposted checks</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Prepay 100 percent of a purchase order amount.</p></td>
<td><p>In AX 2012, you can create prepayments for the line amounts on a purchase order. However, charges and taxes are not included in prepayments.</p>
<p>In cumulative update 6 for Microsoft Dynamics AX 2012 R2, you can prepay either 100 percent or a fixed amount that is equal to the purchase order total. The prepayment can include taxes and charges that have a type of <strong>Customer/Vendor</strong>. For example, if the amount of a purchase order line is 1,000.00, and the sales tax amount is 125.00, the default entry for the prepayment is 1,125.00. In AX 2012, the default prepayment amount was 1,000.00.</p></td>
</tr>
<tr class="odd">
<td><p>Recover pending invoices that have unsaved changes.</p></td>
<td><p>In AX 2012, if the application stops responding when you are entering a vendor invoice, you receive the following message when you restart Microsoft Dynamics AX and open the <strong>Vendor invoice</strong> form: <strong>A pending invoice cannot be displayed because it is in use.</strong></p>
<p>In cumulative update 6 for Microsoft Dynamics AX 2012 R2, this message is replaced with a form that lets you delete pending invoices that have unsaved changes, so that you can continue to work with the invoice.</p></td>
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
<td><p>New options for configuring workflows for vendor invoices</p></td>
<td><p>The following options for vendor invoice workflows are added:</p>
<ul>
<li><p>You can create conditions that are based on values in purchase order fields.</p></li>
<li><p>The <strong>Vendor invoice lines</strong>.<strong>Procurement category</strong> property now includes hierarchical operators for <strong>contains</strong>, <strong>begins with</strong>, <strong>is</strong>, and <strong>is not</strong>.</p></li>
</ul>
<p>For more information about vendor invoice workflows, see <a href="set-up-vendor-invoice-workflows.md">Set up vendor invoice workflows</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8

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
<td><p>(Public sector) Create one or more one-time vendor accounts at the same time as you create invoices for those vendors.</p></td>
<td><p>When approval or a contract in the form of a purchase order is not required, you can quickly create invoices at the same time as you create records for the vendors. You can generate an account for a vendor directly from the invoice form. You can also import a CSV file that has information about multiple one-time vendors and corresponding invoices, and create vendor accounts and accompanying invoices.</p>
<p>For more information, see <a href="create-a-one-time-vendor-and-invoice-public-sector.md">Create a one-time vendor and invoice (Public sector)</a> and <a href="import-and-create-one-time-vendors-and-invoices-public-sector.md">Import and create one-time vendors and invoices (Public sector)</a>.</p></td>
</tr>
</tbody>
</table>

  


