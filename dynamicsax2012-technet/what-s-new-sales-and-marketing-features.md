---
title: "What's new: Sales and marketing features"
TOCTitle: Sales and marketing features
ms:assetid: 2725b7ec-718a-49cb-bb68-0fe8fd6dd271
ms:mtpsurl: https://technet.microsoft.com/library/Dn507147(v=AX.60)
ms:contentKeyID: 59623236
author: Khairunj
ms.date: 11/26/2014
mtps_version: v=AX.60
---

# What's new: Sales and marketing features 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Sales and marketing](sales-and-marketing.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

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
<td><p>Case management in Enterprise Portal for Microsoft Dynamics AX</p></td>
<td><p>You can use case management in Enterprise Portal to access a list of current cases and create new cases. You can access the case information that you require, regardless of whether you are an internal employee or an external worker for the company.</p>
<p>For more information, see <a href="managing-cases.md">Managing cases</a>.</p></td>
</tr>
<tr class="even">
<td><p>Associate contacts with multiple parties in the same organization</p></td>
<td><p>To expand your network, and to obtain new customers and vendors, you can now associate contacts with multiple parties in the same organization.</p>
<p>For more information, see <a href="associate-contact-information-with-a-contact.md">Associate contact information with a contact</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Knowledge articles and case management</p></td>
<td><p>The addition of case management lets you create knowledge articles in what was previously known as the encyclopedia. These knowledge articles can help customer service representatives resolve specific cases. Access to documents, links, and other information can be grouped logically into case categories for the accumulated organizational knowledge of the company. The knowledge articles can also be ranked or scored to indicate how valuable the information is for helping users quickly find the most common solution to an issue.</p>
<p>For more information, see <a href="store-a-knowledge-article.md">Store a knowledge article</a>.</p></td>
</tr>
<tr class="even">
<td><p>Case management in the Microsoft Dynamics AX client</p></td>
<td><p>Case management can help you track cases that customers bring forward, so that you can resolve issues, answer questions, or replace purchased items. You can create, assign, plan, resolve, follow up on, and analyze cases.</p>
<p>For more information, see <a href="case-management.md">Case management</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Updates to the address book</p></td>
<td><p>Updates to the address book include enhanced contact synchronization with Microsoft Outlook.</p>
<p>You can now define multiple purposes for multiple addresses.</p>
<p>For more information, see <a href="synchronize-with-microsoft-outlook.md">Synchronize with Microsoft Outlook</a>.</p></td>
</tr>
<tr class="even">
<td><p>Decouple order management from inventory control</p></td>
<td><p>The pain point that is caused by the tight integration of order handling and the inventory subsystem in Microsoft Dynamics AX 2009 has been addressed. Although this integration is convenient for organizations that have many transaction types that involve inventory and costing, it is inappropriate for organizations where inventory might not be used at all for inbound receipts. This integration is also less important for professional service organizations where the outbound services or deliveries do not involve inventory at all.</p>
<p>For sales, the current tight integration with the inventory subsystem becomes flexible through the introduction of the following capabilities:</p>
<ul>
<li><p>You can make sure that sales order lines and sales quotation lines for products of the service type do not create inventory transactions.</p></li>
<li><p>You can make sure that, when this behavior is required, sales order and sales quotation lines for products of the item type do not create inventory transactions. This scenario typically occurs when a used fixed asset is sold.</p></li>
<li><p>You can sell items that are not defined in the item table. This kind of order is essentially a “free text” order.</p></li>
</ul>
<p>A category relation on sales order and sales quotation lines is introduced to govern posting profiles and statistics.</p>
<p>For more information, see the Microsoft Dynamics AX Supply chain management team blog post <a href="https://blogs.msdn.com/b/dynamicsaxscm/archive/2011/06/01/service-products-in-dynamics-ax-2012.aspx">Service products in Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Stocked inventory policy</p></td>
<td><p>A new method for setting up a stocked inventory policy for an item is introduced. The inventory policy is determined by the Stocked item model group attribute. You can now convert existing or upgraded service products to use the &quot;not stocked” inventory policy. The process for changing the inventory policy can be run for one or more service products in one or more legal entities, and can be run multiple times for different products. You can run the conversion either immediately after you upgrade to AX 2012 or at any time after upgrade.</p>
<p>For more information, see <a href="set-up-items-and-services-for-not-stocked-trade.md">Set up items and services for not stocked trade</a>.</p></td>
</tr>
<tr class="even">
<td><p>Sales and purchase agreement report</p></td>
<td><p>When you confirm a sales agreement or a purchase agreement, you can print the confirmation, and can send a copy to the customer or vendor. You can view or print any version of a sales or purchase agreement in the <strong>Purchase agreement confirmations</strong> form. You can also print a status report that provides information about the fulfillment of a sales or purchase agreement.</p>
<p>For more information, see <a href="print-the-status-of-a-sales-agreement.md">Print the status of a sales agreement</a> and <a href="print-the-status-of-a-purchase-agreement.md">Print the status of a purchase agreement</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Trade agreement enhancements</p></td>
<td><p>Trade agreements are now created and maintained in journals. This change allows for better control, usability, and transparency. Microsoft Dynamics AX now supports one view that includes all trade agreements for a selected set of items, customers, and vendors. Microsoft Dynamics AX also supports separate roles for creating or maintaining trade agreements, and for approving, bulk updating, and controlling date types in trade agreements.</p>
<p>In earlier versions of Microsoft Dynamics AX, changes to an order or an order line could indirectly cause the trade agreements to be reevaluated. This reevaluation could overwrite values that had been entered manually or entered by an external source. External sources include sales quotations, project quotations, purchase requisitions, requests for quotation (RFQs), purchase or sales agreements, projects, Microsoft Dynamics AX Application Integration Framework (AIF), or Enterprise Portal. Now, configuration settings can prevent unintended reevaluation of trade agreements.</p>
<p>The smart rounding concept has also been introduced. Smart rounding is a type of psychological pricing or price ending that is based on the marketing theory that prices have a psychological impact on people. Smart rounding pertains to unusual prices that are slightly less than a round number, such as USD 19.99. Smart rounding can be applied after bulk adjustment of trade agreements, or it can be applied automatically after a unit price has been calculated, based on a generic currency and an exchange rate. Date type control enables trade agreements to be evaluated, based not only on the entry dates but also on the requested dates.</p>
<p>For more information, see <a href="https://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_the_agreement_framework_ax2012.pdf">Implementing the Agreement Framework</a>.</p></td>
</tr>
<tr class="even">
<td><p>Delivery schedule</p></td>
<td><p>A user can split an order line into multiple deliveries, but can retain the price and other order conditions from the original order line.</p>
<p>The feature is implemented on the following documents:</p>
<ul>
<li><p>Sales quotation</p></li>
<li><p>Sales order</p></li>
<li><p>Purchase order</p></li>
</ul>
<p>Delivery schedules introduce the following features:</p>
<ul>
<li><p>A simple interface lets you create and maintain delivery schedule lines.</p></li>
<li><p>All main processes are enabled for delivery lines.</p></li>
<li><p>You can allocate charges to the delivery lines.</p></li>
<li><p>You can override default prices and conditions on delivery lines.</p></li>
</ul>
<p>For more information, see <a href="about-delivery-schedules.md">About delivery schedules</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhanced sales agreement functionality</p></td>
<td><p>The blanket sales order functionality has been redesigned and renamed “sales agreement.” Whereas blank sales orders were previously handled in the Sales order details form, sales agreements now have their own simplified form. Some of the changes are as follows:</p>
<ul>
<li><p>Microsoft Dynamics AX supports both value-based and quantity-based sales agreements.</p></li>
<li><p>You can order certain products and procurement categories directly by using the new <strong>Sales agreements</strong> form.</p></li>
<li><p>You can apply the terms and conditions of a sales agreement, such as the prices and discounts, when you create an order by using the <strong>Sales order</strong> form.</p></li>
<li><p>You can control whether to search for sales agreements when sales order lines are created indirectly, such as by intercompany orders.</p></li>
<li><p>You can define a validity period for a sales agreement. The requested ship date of a sale must be in the validity period.</p></li>
<li><p>You can put sales agreements on hold to control whether those sales agreements are available to sales agents during ordering.</p></li>
</ul>
<p>For more information, see <a href="about-sales-agreements.md">About sales agreements</a>.</p></td>
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
<td><p>Update the name of a party from the party record</p></td>
<td><p>You can update the name of a party record in the party record's form or in the role form of the party record. For example, you can update the name of a customer from either the <strong>Party</strong> form or the <strong>Customer</strong> form.</p>
<p>For more information, see <a href="update-a-party-record-name-or-view-name-changes.md">Update a party record name or view name changes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to Sales and marketing Role Centers and the reporting information that is provided</p></td>
<td><p>In AX 2012 R2 the Sales and marketing Role Centers have been updated to provide more timely and relevant data that is related to the user's role and organization. Additionally, a new Sales and marketing cube has been added.</p></td>
</tr>
<tr class="odd">
<td><p>Update, in bulk, the list of party records that are assigned to an address book</p></td>
<td><p>When you update the list of party records that are assigned to an address book, you can update the list of records as a group instead of one record at a time.</p>
<p>For more information, see <a href="add-or-remove-multiple-parties-in-an-address-book.md">Add or remove multiple parties in an address book</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate a lead or opportunity record from a campaign or call list target record</p></td>
<td><p>You can generate a lead or opportunity record directly from the target record list of a campaign or call list. The campaign or call list information that is relevant to the new lead or opportunity record is automatically included in the new record.</p>
<p>For more information, see <a href="generate-a-lead-or-opportunity-record-from-a-campaign-or-call-list-target.md">Generate a lead or opportunity record from a campaign or call list target</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Cases are secured by case category</p></td>
<td><p>You can grant permission to view and update cases, based on the case category type and the user's security role.</p>
<p>For more information, see <a href="assign-security-roles-to-case-category-types.md">Assign security roles to case category types</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012

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
<td><p>Preserve a reservation for a partial quantity of an item</p></td>
<td><p>When you process a sales order and create a purchase order because of insufficient stock of an item, any existing reservation for a partial quantity is preserved.</p>
<p>Previously, the existing reservation was canceled if you processed a sales order by reserving the available stock of an item and then, before materials requirement planning (MRP) was run, created a purchase order for an additional quantity that was required to complete the order.</p>
<p>For more information, see <a href="reserve-inventory-automatically-for-a-sales-order.md">Reserve inventory automatically for a sales order</a>.</p></td>
</tr>
<tr class="even">
<td><p>Cancel all lines on a sales order</p></td>
<td><p>You can cancel all order lines on a sales order in a single step. Previously, you had to cancel each order line on a sales order individually.</p>
<p>You can also select multiple sales orders and cancel all the order lines for those sales orders. If some order lines that you select were already delivered, you receive a message that states that the order lines have already been delivered and cannot be canceled.</p>
<p>For this feature, a <strong>Cancel</strong> button was added in the <strong>Maintain</strong> group on the <strong>Action Pane</strong> on the <strong>Sales order</strong> tab in the <strong>All sales orders</strong> form.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/aa585863(v=ax.60)">Sales orders (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Validate and post trade agreement journals more efficiently</p></td>
<td><p>You can update multiple sales prices and apply them to the related trade agreements. In cumulative update 6, you can validate and post changes to trade agreements in batches. This feature lets you control the timing and frequency of validation and posting to best suit your business.</p>
<p>For more information, see <a href="validate-and-post-trade-agreement-journal-lines.md">Validate and post trade agreement journal lines</a>.</p></td>
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
<td><p>Calculate the sales price of an item by using an attribute-based pricing formula</p></td>
<td><p>You can now calculate the sales price of an inventory item by using an attribute-based pricing formula. An attribute-based pricing identifier can be associated with a trade agreement for a specific batch of items. When a sales order that uses the trade agreement is invoiced, the net amount is adjusted according to the attribute values that are registered for the inventory batches that are received or produced.</p>
<p>For more information, see <a href="create-price-calculations-for-sales-order-items-that-have-a-potency.md">Create price calculations for sales order items that have a potency</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX2012 R3 CU8

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
<td><p>Integrate Microsoft Exchange Server with Microsoft Dynamics AX.</p></td>
<td><p>In Microsoft Dynamics AX 2012 R3 CU8, you can integrate with Microsoft Exchange Server, as an alternative to the existing Microsoft Outlook integration. This integration allows you to synchronize Exchange appointments, tasks, and contacts with Microsoft Dynamics AX. This integration enables employees who work in a remote desktop or terminal server environment to efficiently leverage the integration feature.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

In previous releases of Microsoft Dynamics AX, you were required to track serial numbers in inventory as an inventory dimension. In Microsoft Dynamics AX 2012 R3, you are no longer required to register serial numbers in inventory. You can now also register serial numbers during the sales process when you prepare the packing slip or the invoice for a sales order. For example, this is useful if you want to use serial numbers only in the sales and return processes for tracing the order history of serialized items without impacting the performance of your inventory processes. Typically, this is needed in order to fulfill service and warranty requirements.

You can register serial numbers on the packing slip or invoice either by entering them manually or by using a scanner. If a serial number is not available, you can mark it as unreadable and post the packing slip. You can update the serial numbers when they become available.

The following list illustrates some of the scenarios that this new feature is intended for:

  - Registering serial numbers for items on sales orders on the packing slip or invoice.

  - Customer pickup of sales orders with serialized items.

  - Partial delivery and invoicing of sales orders with serialized items.

  - Correcting packing slips and invoices with serialized items.

  - Returning serialized items.

  - Tracing the history of orders that include serialized items.

  


