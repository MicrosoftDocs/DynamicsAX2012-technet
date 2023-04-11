---
title: Work with installment billing
TOCTitle: Work with installment billing
ms:assetid: 38775079-c8da-4a98-98e6-057d01e6cef7
ms:mtpsurl: https://technet.microsoft.com/library/Dn497738(v=AX.60)
ms:contentKeyID: 62200054
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRInstallmentSetup
- installment billing
- installment plan
- payment schedule
audience: Application User
ms.search.region: Global
---

# Work with installment billing 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can set up a payment schedule that lets customers pay in installments over time. If you associate a payment schedule with a call center catalog, call center customers can use installment billing as the method of payment for their orders. This topic describes how to set up and use installment billing in a call center.

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
<td><p>Set up a call center. You must select the <strong>Enable order completion</strong> check box in the call center settings. Additionally, you must add the user who creates sales orders to the list of users for the call center channel. For more information, see <a href="set-up-a-call-center.md">Set up a call center</a>.</p>
<p>Set up credit cards as a payment method, unless all installment payments are on account. For more information, see <a href="set-up-payment-methods-call-center.md">Set up payment methods (Call center)</a>.</p>
<p><a href="create-call-center-catalogs.md">Create call center catalogs</a></p></td>
</tr>
</tbody>
</table>


## 1\. Set up a payment schedule

First, set up a payment schedule in **Accounts receivable**. The payment schedule specifies the number of payment installments and the amount that the customer pays per installment. For more information, see [Payment schedules (form)](https://technet.microsoft.com/library/aa572068\(v=ax.60\)).

## 2\. Add the payment schedule to a call center catalog

Next, add the payment schedule to the catalog that the call center is using. The payment schedule then becomes available as one of the payment options in the **Sales order** form.

To add a payment schedule to a catalog, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**.

2.  Select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  On the **Action Pane**, in the **Call center** group, click **Payment schedules**.

4.  Click **New**, and then select a payment schedule.

## 3\. Set parameters for installment billing

Next, set the options for installment billing in the **Call center parameters** form.

To set parameters for installment billing, follow these steps.

1.  Click **Call center** \> **Setup** \> **Call center parameters**.

2.  In the left pane, click **Payment**, and then set the options on the **Installment plan** FastTab.
    
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
    <td><p><strong>Authorization</strong></p></td>
    <td><p>Specify whether an installment payment by credit card is submitted to a processor for authorization on the order date or the date of the first installment.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Apply charges</strong></p></td>
    <td><p>Specify whether charges on the sales order header are applied to the installment plan or to another payment method.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Ship complete</strong></p></td>
    <td><p>A selected check box indicates that sales orders that have installment plans are shipped complete by default.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Installment bill days</strong></p></td>
    <td><p>The number of days before the due date of an installment payment to generate a letter to the customer.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Adjustment method</strong></p></td>
    <td><p>The method to use to adjust payments if the total payment amount changes.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reauthorization limit</strong></p></td>
    <td><p>The maximum number of times that an installment payment by credit card can be resubmitted to the processor for authorization if the payment is declined.</p>
    <p>After the limit is reached, the payment is added to the queue for review in the <strong>Installment payments authorization</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Accelerate payments</strong></p></td>
    <td><p>A selected check box indicates that, if the limit that is set in the <strong>Reauthorization limit</strong> field is reached, the remaining payment balance is due.</p></td>
    </tr>
    </tbody>
    </table>


## 4\. Enable installment billing for customers and products

Next, enable installment billing for specific customers and products. You can also optionally specify which payment schedule to use for each customer or product.

To enable installment billing for customers, follow these steps.

1.  Click **Call center** \> **Common** \> **All customers**.

2.  Select a customer, and then, on the **Action Pane**, click **Edit**.

3.  On the **Payment defaults** FastTab, select the **Installment eligible** check box.

4.  Optional: If you want to enable installment payments on account, select the **Allow on account** check box.

To enable installment billing for products, follow these steps.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a product, and then, on the **Action Pane**, click **Edit**.

3.  On the **Sell** FastTab, in the **Installments** section, select the **Installment eligible** check box.

4.  Optional: If you want to specify one or more payment schedules for the product, on the **Setup** tab, click **Payment schedules**. Then select all the payment schedules that you require.

## 5\. Use installment billing in a sales order

After you've added a payment schedule to a call center catalog, and enabled installment billing for customers and products, you can use installment billing as a payment option for call center orders.

To use installment billing in a sales order, follow these steps.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  Create a new sales order for a customer and products that are eligible for installment billing.

3.  On the **Action Pane**, in the **Maintain** group, click **Complete**.

4.  In the **Sales order summary** form, on the **Action Pane**, click **Payments**.

5.  In the **Customer payments** form, on the **Action Pane**, click **Installment**.

6.  In the **Installment payments** form, in the **Schedule** section, select a payment schedule.
    
    The bottom of the form displays a list of installment payments, and includes the due date, amount, and status for each.

7.  In the **Payment** section, select a payment method. For installment payments, the customer can use a credit card or on-account payment.

8.  If you selected the credit card method of payment, enter the card details.

9.  Close the **Installment payments** form and the **Customer payments** form.

10. In the **Sales order summary** form, click **Submit**.
    
    You can now invoice the order and post the invoice.

## 6\. Process installment billing payments

On the date that each installment payment is due, you must process installment payments. For credit card payments, the processing submits the payments for authorization and settles the transaction. For on-account payments, the payment is added to the balance of the customer's account.

To process an installment payment, follow these steps.

1.  Click **Call center** \> **Periodic** \> **Installment** \> **Process installment payments**.

2.  On the **General** tab, in the **Processing date** field, select the due date of the installment payment to process.
    
    You can also specify which payment schedule and sales order to process.

3.  Optional: On the **Batch** tab, set the options for batch processing.

4.  Click **OK**.

If an installment payment by credit card cannot be authorized by the payment processor, you can handle the authorization manually.

To authorize a credit card payment, follow these steps.

1.  Click **Call center** \> **Journals** \> **Payment management** \> **Credit cards** \> **Installment payments authorization**.

2.  If the payment appears on the **Pending authorization** tab, select the payment, and then follow one of these steps:
    
      - To authorize the payment, click **Manually authorize**. You must enter an authorization code that you have obtained from the payment service.
    
      - To resubmit the payment for authorization, click **Process**.
    
      - To decline the payment, click **Manually decline**, and then enter a decline reason code.
    
    –or–
    
    If the payment appears on the **Declined** tab, select the payment, and then follow one of these steps:
    
      - To decline the payment, click **Manually decline**, and then enter a decline reason code.
    
      - To resubmit the payment for authorization, click **Process**.

3.  Optional: If the payment information that was originally entered in the sales order is incorrect, use the **Sales order** button to modify the information.

## 7\. Close installment orders

After all the installment payments for a sales order have been processed, you can close the order.

To close all the sales orders for which installment payments have been completed, follow these steps.

1.  Click **Call center** \> **Periodic** \> **Installment** \> **Close installment orders**.

2.  Set the options for batch processing, and then click **OK**.

## Related tasks

[Apply payments in sales orders](apply-payments-in-sales-orders.md)

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
<p><strong>Installment billing</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Accounting manager (to set up a payment schedule)</p>
<p>Sales manager (to set up installment billing parameters, enable installment billing for products and customers, and authorize credit card payments</p>
<p>Sales clerk (to create a sales order and process installment payments)</p></td>
</tr>
</tbody>
</table>


## See also

[Payment schedules (form)](https://technet.microsoft.com/library/aa572068\(v=ax.60\))

  


