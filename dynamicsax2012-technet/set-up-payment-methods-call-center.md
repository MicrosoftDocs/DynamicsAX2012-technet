---
title: Set up payment methods (Call center)
TOCTitle: Set up payment methods (Call center)
ms:assetid: 24bcd52c-c82c-4f73-8d1e-bfbf8ff85345
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497730(v=AX.60)
ms:contentKeyID: 62200044
ms.date: 05/09/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailStoreTenderTypeTable
- call center credit card
- call center payment
- payment method
- credit card payment
- call center payment method
- gift card payment
audience: Application User
ms.search.region: Global
---

# Set up payment methods (Call center) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up payment methods for a call center. The payment methods that are used in other channels in Microsoft Dynamics AX 2012 for Retail, such as cash, checks, credit cards, and gift cards, can also be used in call centers. After you have set up a payment method for a call center, it appears as one of the options in the **Payments** section of the **Sales order** form for call center users.

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
<td><p>Required setup tasks</p></td>
<td><p><a href="set-up-a-call-center.md">Set up a call center</a></p></td>
</tr>
</tbody>
</table>


## 1\. Create payment methods in Retail

First, create payment methods in Retail. You can then add these payment methods to a call center by using the next procedure.

To create payment methods in Retail, follow these steps.

1.  Click **Retail** \> **Setup** \> **Payment methods** \> **Payment methods**.

2.  In the **Payment methods** form, press CTRL+N to create a new payment method.

3.  In the **Payment method** field, enter a unique name for the payment method.

4.  In the **Payment method name**, enter a brief description of the payment method.

5.  In the **Default function** field, select a function. The following functions are typically assigned to payment methods:
    
      - **Normal** – Use this function for currency and gift cards.
    
      - **Card** – Use this function for credit cards, corporate cards, and other forms of card payment except gift cards.
    
      - **Check** – Use this function for personal checks and other negotiable documents.
    
      - **Customer** – Use this function if you extend credit to customers and then collect payment later.

## 2\. Specify payment methods for a call center

Next, specify the payment methods that can be used in the call center.

To specify payment methods for a call center, follow these steps.

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Call centers**.

2.  On the **Set up** tab, on the **Action Pane**, click **Payment methods**.

3.  Click **New**, and then, in the **Payment method** field, select a payment method in the list.

4.  On the **Posting** FastTab, select an account type and an account number to use for posting in the ledger.

5.  Repeat steps 3 and 4 to create a new record for each payment method that you require.

## 3\. Set parameters for call center payments

In the **Call center parameters** form, you can set options that determine how payments are handled.

To set up parameters for call center payments, follow these steps:

1.  Click **Call center** \> **Setup** \> **Call center parameters**.

2.  In the left pane, click **Payment**, and then set the payment options in each section.
    
    In the **Credit card authorizations** section:
    
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
    <td><p><strong>Future orders</strong></p></td>
    <td><p>A selected check box indicates that a customer’s credit card information can be used for future orders.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Delay authorization</strong></p></td>
    <td><p>A selected check box indicates that payments are not submitted for authorization for future orders if the sales order does not have reserved inventory.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Future order days</strong></p></td>
    <td><p>The number of days before an order is considered to be a future order.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Retry on submit</strong></p></td>
    <td><p>A selected check box indicates that the system retries a credit card that is declined when the sales order is submitted, if the value in the <strong>Reauthorization limit</strong> field is more than 0 (zero).</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Reauthorization limit</strong></p></td>
    <td><p>The number of times that a credit card that is declined can be resubmitted. After the limit is reached, the payment is considered to be declined.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reserve inventory if authorization expired</strong></p></td>
    <td><p>A selected check box indicates that the picking program reserves inventory even if the authorization on a credit card payment is expired.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Authorize continuity child order</strong></p></td>
    <td><p>When continuity child orders are created, the system tries to authorize credit card payments if both the following conditions are met:</p>
    <ul>
    <li><p>This check box is selected.</p></li>
    <li><p>The system is set up to handle online credit card authorization.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>
    
    In the **Check** section:
    
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
    <td><p><strong>Threshold amount</strong></p></td>
    <td><p>The maximum amount for a check payment before the payment is put on check hold.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number of days</strong></p></td>
    <td><p>The number of days that a sales order is put on hold if a check payment for the order exceeds the value in the <strong>Threshold amount</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Overpaid percentage</strong></p></td>
    <td><p>The maximum amount, as a percentage, of an overpayment by check. If this percentage is exceeded, the sales order must be reviewed.</p>
    <p>For example, if the value <strong>20</strong> is entered here, the order must be reviewed if the overpayment amount is more than 20% of the total owed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Underpaid percentage</strong></p></td>
    <td><p>The maximum amount, as a percentage, of an underpayment by check. If this percentage is exceeded, the sales order must be reviewed.</p>
    <p>For example, if the value <strong>20</strong> is entered here, the order must be reviewed if the underpayment amount is more than 20% of the total owed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Allow out of balance</strong></p></td>
    <td><p>A selected check box indicates that sales orders that are overpaid or underpaid can be processed.</p></td>
    </tr>
    </tbody>
    </table>
    
    In the **Order credits** section:
    
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
    <td><p><strong>Credit to account</strong></p></td>
    <td><p>A selected check box indicates that customer credits are on account by default.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum amount</strong></p></td>
    <td><p>The maximum amount that can be credited to a sales order, in the company currency.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Price match charges code</strong></p></td>
    <td><p>The markup code for the miscellaneous charge that is applied to returns that have a price-matched line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Journal name</strong></p></td>
    <td><p>The name of the journal from which the system takes posting information for order credits.</p></td>
    </tr>
    </tbody>
    </table>



> [!NOTE]
> <P>The <STRONG>Accounts receivable parameters</STRONG> form also includes settings that affect credit card transactions and other aspects of payment processing. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa576993(v=ax.60)">Accounts receivable parameters (form)</A>.</P>



## Next step

Before you can use any payment methods in the **Sales order** form, the **Enable order completion** check box must be selected in the channel settings for the call center. For more information, see [Set up a call center](set-up-a-call-center.md).

If you're using credit cards in a call center, you must complete several other setup procedures before the cards can be used for payment. For more information, see [Set up card types and card numbers](set-up-card-types-and-card-numbers.md), [Set up Payment Services](set-up-payment-services.md), and [Set up credit card authorizations](set-up-credit-card-authorizations.md).

If you're using gift cards in a call center, you must set up gift cards in the products list. For more information, see [Set up gift cards](set-up-gift-cards.md). Both physical gift cards and electronic gift cards (gift cards that are sent by email) can be used in call center orders.

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
<p><strong>Retail gift card</strong> configuration key (if you use gift cards)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Retail operations manager</p>
<p>Sales manager</p></td>
</tr>
</tbody>
</table>


## See also

[Apply payments in sales orders](apply-payments-in-sales-orders.md)

[Sell gift cards or add funds to them](sell-gift-cards-or-add-funds-to-them.md)

[Handle payment issues](handle-payment-issues.md)

  


