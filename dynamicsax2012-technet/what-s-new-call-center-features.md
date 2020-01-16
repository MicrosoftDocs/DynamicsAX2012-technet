---
title: "What's new: Call center features"
TOCTitle: Call center features
ms:assetid: 8b176114-3f7b-425d-8ff7-ab3b721dfbe4
ms:mtpsurl: https://technet.microsoft.com/library/Dn600261(v=AX.60)
ms:contentKeyID: 62200290
author: Khairunj
ms.date: 04/29/2014
mtps_version: v=AX.60
---

# What's new: Call center features 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

We have added the call center as a new type of retail channel in Microsoft Dynamics AX 2012 R3. New call centers and call center catalogs are created in the **Retail** module. Many tasks that are related to the setup and management of a call center are performed in the new [Call center](call-center.md) module. For more information, see the following table.

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
<td><p>A new retail channel type is added: call center</p></td>
<td><p>In a call center, workers take customer orders over the phone and create sales orders. Call centers can be added to organization hierarchies, and can be managed together with online stores and retail stores.</p>
<p>New call centers are set up in the <strong>Retail</strong> module. Many typical management tasks for a call center are performed in the <strong>Call center</strong> module.</p>
<p>For more information, see <a href="call-center.md">Call center</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create catalogs for call centers, and use the following new catalog features:</p>
<ul>
<li><p>Catalog snapshot</p></li>
<li><p>Source codes</p></li>
<li><p>Page analysis</p></li>
<li><p>Free products</p></li>
<li><p>Catalog requests</p></li>
</ul></td>
<td><p>Create a digital catalog that contains the products that the call center offers.</p>
<p>The <strong>Catalogs</strong> form contains the following new functionality that is available to users who are associated with a call center:</p>
<ul>
<li><p>Catalog snapshot – Save catalog data as it exists at the time of publication.</p></li>
<li><p>Source codes – Set up catalog source codes that can be used to track the sales that are associated with a specific catalog version.</p></li>
<li><p>Page analysis – Analyze sales per page area.</p></li>
<li><p>Free products – Save a list of products that are added to a customer's order at no additional charge.</p></li>
</ul>
<p>For more information, see <a href="setting-up-call-center-catalogs.md">Setting up call center catalogs</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Additional item information</p></td>
<td><p>Associate details with sales items. This feature lets you view additional information about the selected line in the sales order form, such as images, purchase order information, delivery dates, and other relevant text.</p>
<p>For more information, see <a href="add-images-and-customer-service-scripts-to-item-information.md">Add images and customer service scripts to item information</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create scripts for call center workers</p></td>
<td><p>Scripts are predefined messages that call center workers can read to customers during order entry. You can create scripts that appear in the sales order form at the time of order entry. You can also translate scripts and store various language versions that call center workers can easily access.</p></td>
</tr>
<tr class="odd">
<td><p>Up-sell and cross-sell products</p></td>
<td><p>Prompt the clerk who enters sales orders to encourage or discourage items during order entry. You can base these prompts on single items or item combinations that are entered at the time of order entry. You can also specify start and end dates for the prompts.</p>
<p>For more information, see Set up cross-sell and up-sell.</p></td>
</tr>
<tr class="even">
<td><p>Continuity programs</p></td>
<td><p>Set up and manage continuity programs, in which customers receive regular product shipments on a predefined schedule.</p>
<p>For more information, see <a href="set-up-continuity-programs.md">Set up continuity programs</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create orders from item lists</p></td>
<td><p>Set up an item list, which is a saved list of products that customers frequently order together. At the time of order entry, a call center worker can open an item list and select the items that the customer wants to order. This feature offers a quick and easy method for creating new orders.</p></td>
</tr>
<tr class="even">
<td><p>Enhanced functionality for direct delivery</p></td>
<td><p>Track the status of a direct delivery purchase order via the associated sales order, and use the direct delivery workbench to create and release purchase orders for direct delivery. You can also specify products that are always sent to customers via direct delivery.</p>
<p>For more information, see <a href="create-direct-deliveries.md">Create direct deliveries</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Perform full-text searches for products in the sales order form</p></td>
<td><p>Search for products from the <strong>Item number</strong> field in the sales order form. You can set up field criteria and parameters to determine how the search is performed. The search results show a list of products that match the search term, and also include availability information for each product in the list.</p>
<p>For more information, see <a href="set-up-product-search-options.md">Set up product search options</a>.</p></td>
</tr>
<tr class="even">
<td><p>Pricing options:</p>
<ul>
<li><p>Price details</p></li>
<li><p>Price overrides</p></li>
<li><p>Discount overrides</p></li>
<li><p>Miscellaneous charge overrides</p></li>
<li><p>Price matching</p></li>
</ul></td>
<td><p>You have precise control over pricing for call center sales orders:</p>
<ul>
<li><p>The <strong>Price details</strong> form provides in-depth information about the pricing for a line item. You can view information about the prices, agreements, and trade agreements that are associated with the selected product. The form also calculates discounts, rebates, margins, and royalties for the order line. For more information, see <a href="enable-price-details-on-orders.md">Enable price details on orders</a>.</p></li>
<li><p>Price overrides track overrides on order lines. A reason code, log, and order event are created.</p></li>
<li><p>Discount overrides let authorized employees change the price of items.</p></li>
<li><p>Miscellaneous charge overrides let authorized users override various charges on a sales order.</p></li>
<li><p>Price matching lets authorized users change the price of an item in response to a competitor’s price. For more information, see <a href="match-prices-for-products.md">Match prices for products</a>.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>View margin alerts</p></td>
<td><p>View the calculated margin values for broker royalties and rebates in the sales order form.</p></td>
</tr>
<tr class="even">
<td><p>Enhanced payment functionality</p></td>
<td><p>Use the following new payment functionality for call center orders:</p>
<ul>
<li><p>Issue and redeem gift cards directly in AX 2012 R3, and add funds to gift cards.</p></li>
<li><p>Use cash and gift cards as payment methods in the sales order form.</p></li>
<li><p>Use multiple payment methods in an order.</p></li>
<li><p>Apply and remove check holds.</p></li>
<li><p>Approve and process check refunds.</p></li>
<li><p>Process overpayments and underpayments.</p></li>
<li><p>Resubmit credit card payments for authorization, or decline credit card payments.</p></li>
<li><p>Approve credit card refunds.</p></li>
<li><p>Process orders that are on hold because the customer is over his or her credit limit.</p></li>
<li><p>View a summary of payment details and payment status in the <strong>Sales order summary</strong> form.</p></li>
</ul>
<p>For more information, see <a href="working-with-payments-call-center.md">Working with payments (Call center)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Default sales tax groups</p></td>
<td><p>Use default sales tax groups to create and view default priorities for calculating sales tax groups. This feature lets you match address fields to the appropriate tax group for each order.</p>
<p>For more information, see <a href="set-up-automatic-sales-tax-group-assignments.md">Set up automatic sales tax group assignments</a>.</p></td>
</tr>
<tr class="even">
<td><p>Use coupons in sales orders</p></td>
<td><p>Create coupons that can be applied to call center sales orders. Coupons can specify either a percentage or a specific amount that is subtracted from the order total. You can also create coupons that are intended for one-time use.</p></td>
</tr>
<tr class="odd">
<td><p>Use installment payments in sales orders</p></td>
<td><p>Set up a payment schedule that appears as one of the payment options in the sales order form for call center users. The following new features have been added:</p>
<ul>
<li><p>You can specify which individual customers and products are eligible for installment billing.</p></li>
<li><p>Installment billing can use &quot;on account&quot; payment.</p></li>
<li><p>You can associate a payment schedule with a catalog.</p></li>
</ul>
<p>For more information, see <a href="work-with-installment-billing.md">Work with installment billing</a>.</p></td>
</tr>
<tr class="even">
<td><p>Broker support</p></td>
<td><p>Ship sales orders from brokers directly to the broker’s customers. The appropriate fee can also be paid to the broker.</p></td>
</tr>
<tr class="odd">
<td><p>Put sales orders on hold</p></td>
<td><p>Create user-defined hold codes that include details about who put the order on hold and when. After a hold is cleared, the order is automatically sent for picking and shipment.</p></td>
</tr>
<tr class="even">
<td><p>Expedite orders</p></td>
<td><p>Set up an expedited shipping mode that can be applied to a sales order or sales order line. When you select the expedited mode, the order or order line is flagged as expedited in the picking list.</p>
<p>You can also set up a mode that indicates low shipping priority for an order.</p>
<p>For more information, see <a href="expedite-orders.md">Expedite orders</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Automatic notification and cancellation for backorders</p></td>
<td><p>Automatically notify customers by email when orders are not shipped by the expected date. You can also configure the system to cancel orders that are not shipped within a specified period after the order date.</p>
<p>For more information, see <a href="set-up-notification-and-cancellation-for-delayed-orders.md">Set up notification and cancellation for delayed orders</a>.</p></td>
</tr>
<tr class="even">
<td><p>Track sales order events</p></td>
<td><p>Define the order details that are tracked for reporting and evaluation.</p>
<p>For more information, see <a href="set-up-order-events.md">Set up order events</a>.</p></td>
</tr>
<tr class="odd">
<td><p>View detailed order status</p></td>
<td><p>View detailed information about the status of sales orders and sales order lines. From the sales order form, you can view status information for the following areas:</p>
<ul>
<li><p>Payments</p></li>
<li><p>Picking and packing</p></li>
<li><p>Delivery</p></li>
<li><p>Invoicing</p></li>
<li><p>Holds</p></li>
<li><p>Backorders</p></li>
<li><p>Returns</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Order notes</p></td>
<td><p>Attach notes to a customer, order, or order line.</p></td>
</tr>
<tr class="odd">
<td><p>Customer letters</p></td>
<td><p>Define letter templates that can be used to generate personalized customer communications.</p></td>
</tr>
<tr class="even">
<td><p>Fraud handling</p></td>
<td><p>Define fraud rules to warn call center workers about potential fraud situations. You can also define special hold codes that are automatically or manually applied to suspicious orders.</p></td>
</tr>
<tr class="odd">
<td><p>Perform RFM analysis on customers</p></td>
<td><p>Track the frequency and monetary value of a customer's previous purchases, and convert this data into a score. The score is displayed in the sales order form whenever the customer places an order and can be viewed by the call center worker who takes the order.</p>
<p>For more information, see <a href="set-up-rfm-analysis.md">Set up RFM analysis</a>.</p></td>
</tr>
<tr class="even">
<td><p>Track customer statistics</p></td>
<td><p>Calculate statistics about customer orders. Data includes the date of the first order, the date of the last order, the total amount that has been invoiced, and the total returns.</p></td>
</tr>
<tr class="odd">
<td><p>Enhanced functionality for customer service</p></td>
<td><p>Use the following new customer service features in a call center:</p>
<ul>
<li><p>Import a file that indicates duplicate customers.</p></li>
<li><p>Import lists of business relations or business prospects.</p></li>
<li><p>Import a change-of-address file. You can inactivate invalid addresses and update addresses.</p></li>
<li><p>Use the new customer service form to perform the following tasks:</p>
<ul>
<li><p>Search for customers by keyword, telephone number, sales order, or customer account number. You can use wildcard characters in customer searches.</p></li>
<li><p>View detailed customer information, such as contact information, notes, sales order lines, and events.</p></li>
<li><p>Track and fulfill customer requests for catalogs.</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Track customer cases</p></td>
<td><p>This feature adds hot alerts to case management. Customer-specific hot alerts automatically prompt the call center user when important customer-specific information is available.</p></td>
</tr>
<tr class="odd">
<td><p>Purge sales history</p></td>
<td><p>Delete old sales orders for a call center. You can still view the sales order numbers and a summary of the details for each sales order.</p></td>
</tr>
</tbody>
</table>

  


