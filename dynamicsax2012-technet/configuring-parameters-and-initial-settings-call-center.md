---
title: Configuring parameters and initial settings (Call center)
TOCTitle: Configuring parameters and initial settings (Call center)
ms:assetid: 480ea5dc-6662-499b-99c3-56bca66a6121
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497744(v=AX.60)
ms:contentKeyID: 62200061
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCROrderParameters
- MsDynAx060.Forms.MCRRefundMethodsTable
- MsDynAx060.Forms.MCROrderParameters
- Forms.MCRRefundMethodsTable
- call center parameters
---

# Configuring parameters and initial settings (Call center) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You must set parameters to configure the **Call center** module for your business. Parameters provide default settings and values that can often be changed in individual records.

For more information about the types of records that are mentioned in this topic, see the appropriate topics in [Setting up and maintaining Call center](setting-up-and-maintaining-call-center.md).

## Setting parameters

To set call center parameters, follow these steps.

1.  Click **Call center** \> **Setup** \> **Call center parameters**.

2.  Use the links in the left pane to navigate to different sections of the **Call center parameters** form. For more information about each setting, see the parameter descriptions later in this topic.

## General parameters

The parameters in the **General** section apply to many areas of **Call center**. The following table describes some of the parameters that you can set.

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
<td><p><strong>Source code required</strong></p></td>
<td><p>Select this check box to indicate that the <strong>Source</strong> field in the <strong>Sales order</strong> form is a required field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Remove reservations for declined payments</strong></p></td>
<td><p>Select this check box to indicate that inventory is no longer reserved for a sales order line if a payment is declined.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Charge reason code required</strong></p></td>
<td><p>Select this check box to indicate that the user must enter a reason code for any miscellaneous charges.</p></td>
</tr>
<tr class="even">
<td><p><strong>Continuity</strong> parameters (multiple)</p></td>
<td><p>For information about continuity parameters, see <a href="set-up-continuity-programs.md">Set up continuity programs</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>First notice days from start</strong></p></td>
<td><p>Specify the number of days after the order date that a notification must be sent to a customer, if the order remains unshipped.</p></td>
</tr>
<tr class="even">
<td><p><strong>Cancellation notice days from start</strong></p></td>
<td><p>Specify the number of days after the order date that a cancellation notice must be sent to a customer, if the order remains unshipped.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Automatic notification and cancellation processing</strong></p></td>
<td><p>Select this check box to enable automatic notification and cancellation for unshipped orders.</p></td>
</tr>
<tr class="even">
<td><p><strong>Number of days</strong></p></td>
<td><p>Specify the number of days after the expected ship date that an order is considered to be backordered.</p></td>
</tr>
</tbody>
</table>


## Holds parameters

The following table describes some of the parameters that you can set for orders that are on hold.

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
<td><p><strong>Submit when cleared</strong></p></td>
<td><p>Select this check box to indicate that an order is submitted for processing after any holds on that order are cleared.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fraud</strong> parameters (multiple)</p></td>
<td><p>For information about fraud parameters, see Setting up fraud alerts.</p></td>
</tr>
</tbody>
</table>


## Payments parameters

The following table describes some of the parameters that you can set for payments.

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
<td><p><strong>Credit card authorizations</strong> parameters (multiple)</p></td>
<td><p>For information about credit card authorizations parameters, see <a href="set-up-payment-methods-call-center.md">Set up payment methods (Call center)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Check</strong> parameters (multiple)</p></td>
<td><p>For information about check parameters, see <a href="set-up-payment-methods-call-center.md">Set up payment methods (Call center)</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Credit card approval amount</strong></p></td>
<td><p>The amount that causes credit card refunds to be put into the approval queue. If the refund amount is less than this amount, the refund is automatically approved.</p></td>
</tr>
<tr class="even">
<td><p><strong>Refund check approval amount</strong></p></td>
<td><p>The amount that causes check payment refunds to be put into the approval queue. If the refund amount is less than this amount, the refund is automatically approved.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Refund methods</strong> button</p></td>
<td><p>Open a form where you can set up refund methods.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print charges</strong></p></td>
<td><p>Select whether miscellaneous charges are printed separately on the invoice or grouped by miscellaneous charge code.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Order credits</strong> parameters (multiple)</p></td>
<td><p>For information about order credits parameters, see <a href="set-up-payment-methods-call-center.md">Set up payment methods (Call center)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Installment plan</strong> parameters (multiple)</p></td>
<td><p>For information about installment plan parameters, see <a href="work-with-installment-billing.md">Work with installment billing</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Enable payment logging:</strong></p></td>
<td><p>Select this check box to indicate that an event is logged in Event Viewer each time that a user views credit card data.</p></td>
</tr>
</tbody>
</table>


## RMA/Return parameters

The following table describes some of the parameters that you can set for return materials authorizations (RMAs) and returns.

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
<td><p><strong>Payment method</strong></p></td>
<td><p>Specify the payment method to use for returns.</p></td>
</tr>
<tr class="even">
<td><p><strong>Source code for exchange</strong></p></td>
<td><p>Select from the following options:</p>
<ul>
<li><p><strong>Default</strong> – Use the default source code for exchanges when an exchange sales order is created.</p>
<p>If this option is selected, set the default in the <strong>Default exchange source code</strong> field.</p></li>
<li><p><strong>Original</strong> – Use the source code from the original order.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Allow expired source code</strong></p></td>
<td><p>Select this check box to indicate that source codes from expired catalogs can be entered in an exchange sales order.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pending return hold</strong></p></td>
<td><p>Specify the hold code to use for an exchange order while the return of the product is pending.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Exchange balance hold</strong></p></td>
<td><p>Specify the hold code to use when the payments for an exchange order don't balance with the total for the original order.</p></td>
</tr>
</tbody>
</table>


## Coupons parameters

For information about coupons parameters, see [Set up coupons for customer orders in the call center](set-up-coupons-for-customer-orders-in-the-call-center.md).

## Display parameters

The following table describes some of the parameters that you can set for display colors.

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
<td><p><strong>Price override line</strong></p></td>
<td><p>Specify the background color for a sales line on which the price has been overridden.</p></td>
</tr>
</tbody>
</table>


## Number sequences

You must set up number sequences that are used when numbered records are created.

## See also

[Call center](call-center.md)

[Setting up and maintaining Call center](setting-up-and-maintaining-call-center.md)

[Working with Call center](working-with-call-center.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

