---
title: Apply payments in sales orders
TOCTitle: Apply payments in sales orders
ms:assetid: 6bda95fa-c712-4988-933d-78abf5291f40
ms:mtpsurl: https://technet.microsoft.com/library/Dn497786(v=AX.60)
ms:contentKeyID: 62200085
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRCustPaymDialog
- Forms.MCRCustPaymTable
- Forms.MCRSalesOrderRecap
- MsDynAx060.Forms.MCRCustPaymDialog
- MsDynAx060.Forms.MCRSalesOrderRecap
- MsDynAx060.Forms.MCRCustPaymTable
- payment method
- credit card payment
- call center payment method
- gift card payment
- multiple payment methods
- sales order payment
audience: Application User
ms.search.region: Global
---

# Apply payments in sales orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

When you create a sales order for a call center, you can enter the customer's payment information directly into the sales order and then submit the payment. This topic describes how to enter and submit payment information for a sales order.

Call centers can accept any of the payment methods that have been set up for the call center, including cash, check, credit card, gift card, and customer accounts. Customers can also use multiple payment methods in a single order.

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
<td><p>Required setup steps</p></td>
<td><p><a href="set-up-payment-methods-call-center.md">Set up payment methods (Call center)</a>.</p>
<p>Select the <strong>Enable order completion</strong> check box in the call center settings. For more information, see <a href="set-up-a-call-center.md">Set up a call center</a>.</p>
<p>Add the user who is creating sales orders to the list of users for the call center channel. For more information, see <a href="set-up-a-call-center.md">Set up a call center</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Use a cash, check, card, or customer account payment in a sales order

To use a cash, check, card, or customer account payment in a call center sales order, follow these steps.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  Create a new sales order, and enter information about the customer and the products that are being purchased.

3.  When you have finished adding order information and are ready to enter payment, on the **Action Pane**, in the **Maintain** group, click **Complete**. The **Sales order summary** form opens.

4.  On the **Action Pane**, click **Payments**. In the **Customer payments** form, click **Add**, and then select the method of payment.

5.  Enter in the payment details. In the **Payment amount** field, enter the amount of the payment that should be made by using the selected method.

6.  Click **OK**, and then confirm that the **Balance** field has been updated to reflect the payment amount.

7.  Close the **Customer payments** form. Review the order details in the **Sales order summary** form, and then click **Submit**.

8.  To verify the status of the payment, close the **Sales order** form, and then, in the **All sales orders** list, press F5 to update the data. Select the sales order that you just created, and then, on the **Action Pane**, click **Payments**. The payment status and balance are displayed in the **Customer payments** form. Some of the statuses are as follows:
    
      - **Paid** – The payment transaction was posted successfully.
    
      - **Authorized** – The card was authorized by the card processor.
    
      - **Not authorized** – The card was not authorized by the card processor.
    
      - **Not submitted** – The payment was not submitted successfully. Either the worker who filled out the order has not submitted the payment yet, or a card was not authorized by the card processor.

For more information about how to handle unsuccessful payments and other payment issues, see [Handle payment issues](handle-payment-issues.md).

## 2\. Use a gift card payment in a sales order

To use a gift card payment in a sales order, follow these steps.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  Create a new sales order, and enter information about the customer and the products that are being purchased.

3.  When you have finished adding order information and are ready to enter payment, on the **Action Pane**, in the **Maintain** group, click **Complete**. The **Sales order summary** form opens.

4.  On the **Action Pane**, click **Payments**. In the **Customer payments** form, click **Add**, and then select the gift card method of payment.

5.  Enter the gift card number and the payment amount.
    

    > [!NOTE]
    > <P>If the balance on the card is not enough to pay the specified amount, a message is displayed that contains details about the balance. If the card balance is zero, a message is displayed that states that the remaining amount on the card cannot be zero.</P>



6.  Click **OK**, and then confirm that the **Balance** field has been updated to reflect the payment amount.

7.  Close the **Customer payments** form. Review the order details in the **Sales order summary** form, and then click **Submit**.

8.  To verify the status of the payment, close the **Sales order** form, and then, in the **All sales orders** list, press F5 to update the data. Select the sales order that you just created, and then, on the **Action Pane**, click **Payments**. The payment status and balance are displayed in the **Customer payments** form. The status should be **Paid**.

## 3\. Use multiple payment methods in a sales order

You can use a combination of payment methods in a sales order.

To use multiple payment methods in a sales order, follow these steps.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  Create a new sales order, and enter information about the customer and the products that are being purchased.

3.  When you have finished adding order information and are ready to enter payment, on the **Action Pane**, in the **Maintain** group, click **Complete**. The **Sales order summary** form opens.

4.  On the **Action Pane**, click **Payments**. In the **Customer payments** form, click **Add**, and then select the first method of payment.

5.  Enter the payment details. In the **Payment amount** field, enter the amount that should be paid by using the first payment method.
    
    –or–
    
    If the customer is paying by credit card, by gift card, or on account, you can use the **Percent amount** field to specify the percentage of the total that should be paid by using that method.

6.  Click **OK**, and then click **Add** to create a second payment record.

7.  Enter the payment details. In the **Payment amount** field, enter the amount that should be paid by using the second payment method.
    
    –or–
    
    If the customer is paying by credit card, by gift card, or on account, in the **Percent amount** field, enter the remaining percentage that should be paid.

8.  Click **OK**, and then confirm that the **Balance** field has been updated to reflect the combined payment amount.

9.  Close the **Customer payments** form. Review the order details in the **Sales order summary** form, and then click **Submit**.

10. To verify the status of the payment, close the **Sales order** form, and then, in the **All sales orders** list, press F5 to update the data. Select the sales order that you just created, and then, on the **Action Pane**, click **Payments**. The payment status and balance are displayed in the **Customer payments** form. The status is listed separately for each payment method.

## Next step

After you have submitted payment information, you can pick and pack the order, and invoice the order.

## Related tasks

[Set up payment methods (Call center)](set-up-payment-methods-call-center.md)

Apply coupons

[Handle payment issues](handle-payment-issues.md)

[Set up gift cards](set-up-gift-cards.md)

[Sell gift cards or add funds to them](sell-gift-cards-or-add-funds-to-them.md)

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
<p><strong>Payment</strong> configuration key</p>
<p><strong>Retail gift card</strong> configuration key (for gift card payments)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales clerk</p></td>
</tr>
</tbody>
</table>

  


