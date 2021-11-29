---
title: Match prices for products
TOCTitle: Match prices for products
ms:assetid: 13061fb3-96a8-4f62-94ec-7d6d4fc53ed4
ms:mtpsurl: https://technet.microsoft.com/library/Dn715953(v=AX.60)
ms:contentKeyID: 62200035
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- price match
- price matching
- Forms.MCRCreateCustCredit
- match prices
audience: Application User
ms.search.region: Global
---

# Match prices for products 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to match prices for products in a call center. The price matching feature lets call center workers match a competitor's price for a product. To match prices, a worker first creates a sales order that uses the regular price of the product and then invoices the order. After the invoice is created, the worker lowers the price to the requested amount by creating a credit that is applied to the customer's account.

You can set a limit on the amount of the credit that is created for a price match. To limit the credit amount, set the maximum amount for an order credit in the call center parameters.

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
<td><p>Set up a call center. You must select the <strong>Enable order completion</strong> and <strong>Enable order price control</strong> check boxes in the call center settings. Additionally, you must add the user who creates sales orders to the list of users for the call center channel. For more information, see <a href="set-up-a-call-center.md">Set up a call center</a>.</p>
<p><a href="set-up-payment-methods-call-center.md">Set up payment methods (Call center)</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set order credit parameters

Set the call center parameters that are related to order credits, such as the journal name, offset account, and charges code to use for the price match credit. You can also set the maximum amount that is allowed for order credits.

To set the parameters for order credits, follow these steps.

1.  Click **Call center** \> **Setup** \> **Call center parameters**.

2.  In the left pane, click **Payment**.

3.  On the **Order credits** FastTab, in the **Journal name** field, select an appropriate journal to use for order credits. Right-click the **Journal name** field, and then select **View details**.

4.  In the **Journal names** form, in the **Offset account** field, select an appropriate offset account to use for the order credit. Set the other options for the journal as you require. Close the **Journal names** form.

5.  In the **Call center parameters** form, set the other order credit parameters. For more information about these parameters, see [Set up payment methods (Call center)](set-up-payment-methods-call-center.md).

## 2\. Match prices for products

To match a price for a product, first create a sales order, and invoice the order. Then create a credit to apply to the order. The amount of the credit is the difference between the original price of the product and the lower price that you want to match.

To match prices for a product, follow these steps.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  Create a sales order, enter payment information, complete the order, and invoice the order.

3.  In the **Sales order** form, on the **Sales order lines** FastTab, click **Update line**, and then click **Price match**.

4.  In the **Price match** form, in the **New price** field, enter the new price for the product. The **Credit amount** field displays the amount of the credit, or the difference between the current price and the new price.

5.  In the **Reason code** field, select a reason code to use for the credit.
    

    > [!NOTE]
    > <P>For more information about how to set up reason codes that you can use for order credits, see <A href="set-up-info-codes.md">Set up info codes</A>.</P>



6.  Select the **Credit to account** check box to credit the customer's account. If this check box is cleared, you can issue the credit by using any other payment method that the call center supports.

7.  On the **Action Pane**, click **OK** to process the credit.

## Related tasks

Create a basic sales order for Call center

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
<p><strong>Payment</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager (to set call center parameters)</p>
<p>Accounts receivable clerk (to invoice sales orders)</p>
<p>Sales clerk (to create sales orders and match prices)</p></td>
</tr>
</tbody>
</table>

  


