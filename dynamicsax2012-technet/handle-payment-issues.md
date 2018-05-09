---
title: Handle payment issues
TOCTitle: Handle payment issues
ms:assetid: 49610949-1930-4d35-ad0b-b51d56ef10a4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497745(v=AX.60)
ms:contentKeyID: 62200062
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRCCAuthManagement
- Forms.MCROutOfBalancePaymentWB
- Forms.MCRCheckHoldWB
- Forms.MCROverCreditLimitWB
- Forms.MCRUpdateCreditLimit
- MsDynAx060.Forms.MCRCheckHoldWB
- MsDynAx060.Forms.MCROverCreditLimitWB
- MsDynAx060.Forms.MCRUpdateCreditLimit
- MsDynAx060.Forms.MCROutOfBalancePaymentWB
- MsDynAx060.Forms.MCRCCAuthManagement
- authorize credit card
- check hold
- process credit card
- out-of-balance payment
- out of balance payment
- decline credit card
---

# Handle payment issues 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A payment transaction for a call center sales order cannot be completed if a credit card was declined, a payment requires authorization, a check hold was placed, a payment is over the credit limit, or a payment is out of balance with the invoiced amount. To process the payment in these cases, you can use one of the procedures that are described in this topic.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Setup steps</p></td>
<td><p><a href="set-up-payment-methods-call-center.md">Set up payment methods (Call center)</a></p></td>
</tr>
</tbody>
</table>


## 1\. Release a check hold

In the call center parameters, you can specify that an order should be placed on hold if a check payment exceeds a certain threshold. For more information, see [Set up payment methods (Call center)](set-up-payment-methods-call-center.md).

To release a check hold, follow these steps.

1.  Click **Call center** \> **Journals** \> **Payment management** \> **Check holds**.

2.  Select a sales order, and then click **Release**.

3.  Close the **Check holds** form.

## 2\. Authorize, decline, or resubmit credit card payments

If you submit a credit card payment from the **Sales order** form and receive a message that states that the card was not authorized, you can handle the authorization manually.

To authorize, decline, or resubmit a credit card transaction, follow these steps.

1.  Click **Call center** \> **Journals** \> **Payment management** \> **Credit cards** \> **Authorization management**.

2.  If the payment appears on the **Pending authorization** tab, select the payment, and then follow one of these steps:
    
      - To authorize the payment, click **Manually authorize**. You must obtain an authorization code from the payment service and enter it.
    
      - To resubmit the payment for authorization, click **Process**.
    
      - To decline the payment, click **Manually decline**, and then enter a decline reason code.

3.  If the payment appears on the **Declined** tab, select the payment, and then follow one of these steps:
    
      - To decline the payment, click **Manually decline**, and then enter a decline reason code.
    
      - To resubmit the payment for authorization, click **Process**.

4.  Optional: Modify the payment information in the sales order, if the information that was originally entered was incorrect:
    
    1.  In the **Credit card authorization management** form, click **Sales order**, and then click **Modify sales order**.
    
    2.  On the **Action Pane**, click **Payments**. Select a payment, and then click **Edit**.
    
    3.  Select the credit card that was declined, click **Delete**, and then click **Add** to create a new payment record.
    
    4.  In the **Payment** form, enter new or corrected information for the credit card payment, and then click **OK**.
    
    5.  Close the **Customer payments** form, and then, in the **Sales order** form, in the **Maintain** group, click **Complete**. Verify the payment details in the **Sales order summary** form, and then click **Submit**.

## 3\. Process overpayments and underpayments

If the total amount of a payment differs from the total order amount by more than the threshold that is defined in the call center parameters, the order is placed on hold. When this happens, you can review the payment and then choose to release the hold, cancel the order, or change the payment information in the original order.

For more information about how to set parameters for overpayments and underpayments, see [Set up payment methods (Call center)](set-up-payment-methods-call-center.md).

To process overpayments and underpayments, follow these steps.

1.  Click **Call center** \> **Journals** \> **Payment management** \> **Out of balance**.

2.  Click either the **Overpaid** tab or the **Underpaid** tab, depending on the type of out-of-balance payment that you want to view.

3.  Select a payment. Then do one of the following actions:
    
      - Click **Release** to release the order for processing.
    
      - Click **Cancel order** to cancel the order.
    
      - Click **Sales order** to modify the payment information in the sales order.

## 4\. Process orders that are on hold because of credit limits

You can set up a customer's account so that a credit limit is specified. If an order total exceeds this limit, the order is placed on hold until you choose to release the hold. For more information about how to set up credit limits, see [Credit limits for customers](credit-limits-for-customers.md).

To process orders that are on hold because of credit limits, follow these steps.

1.  Click **Call center** \> **Journals** \> **Payment management** \> **Credit limit**.

2.  Select a sales order. Then do one of the following actions:
    
      - Click **Release** to release the order for processing.
    
      - Click **Cancel order** to cancel the order.
    
      - Click **Sales order** to modify the payment information in the sales order.
    
      - Click **Edit customer** to modify the credit limit for the customer.

## Related tasks

[Apply payments in sales orders](apply-payments-in-sales-orders.md)

[Manage deductions in the deduction workbench](manage-deductions-in-the-deduction-workbench.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p>
<p><strong>Payment</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager</p></td>
</tr>
</tbody>
</table>


## See also

[Set up payment methods (Call center)](set-up-payment-methods-call-center.md)

[Credit limits for customers](credit-limits-for-customers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

