---
title: About purchase agreements
TOCTitle: About purchase agreements
ms:assetid: 647d630a-06bb-4116-b86f-a79b992e5df8
ms:mtpsurl: https://technet.microsoft.com/library/Aa571142(v=AX.60)
ms:contentKeyID: 44080987
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase agreement
- purchase agreements
audience: Application User
ms.search.region: Global
---

# About purchase agreements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A purchase agreement is a contract that commits an organization to buy a specified quantity or amount by using multiple purchase orders over time. In exchange for this commitment, the buyer receives special prices and discounts. The purchase agreement can apply to a specific quantity of a product, a specific currency amount of a product, or a specific currency amount of the products in a procurement category. The prices and discounts of the purchase agreement override the prices and discounts that are specified in any trade agreements that exist.


> [!NOTE]
> <P>For public sector entities in France, the purchase agreement document is used to represent the marché.</P>



In the **Purchase agreements** form, you can create, apply, and follow up on purchase agreements that exist between your organization and your vendors. For example, after you create a purchase agreement, you can order directly from it.

Every purchase agreement has a validity period that is defined by the person who creates the purchase agreement. The delivery date of a purchase must be in the effective dates of the validity period.

By default, a purchase agreement is on hold. You must change the status of the purchase agreement to **Effective** before you can create a purchase order for the purchase agreement.

## Commitment types

Each line in a purchase agreement is a commitment to buy something. You can use lines from multiple purchase orders to fulfill the commitment. There are four types of commitments:

  - **Product quantity commitment** – You purchase a specific quantity of a product.

  - **Product value commitment** – You purchase a specific currency amount of a product.

  - **Product category value commitment** – You purchase a specific currency amount in a procurement category. The amount can be for a catalog item or a non-catalog item.

  - **Value commitment** – You purchase a specific currency amount of any product or in any procurement category.


> [!IMPORTANT]
> <P>The commitment type, which only specifies whether the purchase agreement is based on a value or a quantity, differs from the commitment document that is used by public sector entities in France. For more information about commitment documents, see <A href="fra-about-commitments-public-sector.md">(FRA) About commitments (Public sector)</A>.</P>



## Pricing terms for purchase agreements

Pricing terms can vary, depending on the type of commitment. The pricing terms from purchase agreements override any other pricing terms that are set up for trade agreements.

The following table describes the price-related fields that are affected by each commitment type. Fields that contain Yes can be updated on an order line.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Commitment type</p></th>
<th><p><strong>Unit price</strong></p></th>
<th><p><strong>Price unit</strong></p></th>
<th><p><strong>Discount percent</strong></p></th>
<th><p><strong>Cash discount amount</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Product quantity commitment</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Product value commitment</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Yes</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Product category value commitment</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Yes</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Value commitment</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Yes</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Policies for purchase agreements

The following policies affect the way that the link between a purchase agreement commitment and the corresponding purchase order lines works:

  - **Max is enforced** – The total quantity or amount for all order lines cannot exceed the quantity or amount that is specified on the related commitment.

  - **Price and discount is fixed** – The price on an order line and the price on the related commitment cannot differ. If the price is changed on the order line, the link to the commitment is broken. If the link is broken, the order line does not contribute to the fulfillment of the commitment.

  - **Minimum release amount** and **Maximum release amount** – If an amount is specified, a message is displayed if you make any change to an order line that causes the order line to be different from the related commitment.

## Fulfillment calculations for purchase agreements

The **Fulfillment** tab on the **Line details** FastTab in the **Purchase agreements** form displays fulfillment quantities and amounts.

In the **Fulfillment** area, you can view the total quantities and amounts for all order lines that are linked to the specified purchase agreement. You can also view the remaining amount or quantity that is required to fulfill the commitment.

In the **Agreement** area, you can view the quantities and amounts from the specified purchase agreement. These quantities and amounts are the total quantities and amounts that were committed.

## Confirmations and version history for purchase agreements

When you confirm a purchase agreement, the current version of the purchase agreement is stored in a history table. If you change the purchase agreement, you can confirm it again to store another version of the purchase agreement in the history.

If you do not confirm a purchase agreement, you can still use it to create purchase orders. However, history information for the purchase agreement is not stored.

You can preview or print all revisions of the confirmations. You can then share the revisions with your vendor to obtain approval.

## Applying purchase agreements in the ordering process

You can place an order by using the **Purchase order** form. You can then apply the terms of a purchase agreement to the header of the purchase order. Terms can include information, such as the payment terms, delivery terms, and delivery address. You can select a purchase agreement when you create a new purchase order. If one or more order lines are for products and categories that are specified in the purchase agreement, the prices and discounts from the purchase agreement are used for those lines. Additionally, the amount or quantity on the order line is registered on the commitment and contributes to the fulfillment of the commitment. The same purchase order can include both lines that are not related to a purchase agreement and lines that have a commitment for a purchase agreement. For more information, see [Create a purchase release order](create-a-purchase-release-order.md).

## Automatic search for purchase agreements

In some situations where purchase orders are created indirectly, you can control whether Microsoft Dynamics AX should automatically search for applicable purchase agreements. For example, you might do this when you are automatically firming planned purchase orders or creating purchase orders that are based on sales orders.

## Purchase agreements and intercompany trace

Intercompany trading relationships can be created between vendor accounts and customer accounts that are in different legal entities. When a sales order or purchase order is created for one of the parties, an intercompany order chain is created. In the order chain, the sales order and purchase order are created in the appropriate legal entities. For more information, see [Set up vendors, customers, and items for intercompany trade](set-up-vendors-customers-and-items-for-intercompany-trade.md), [Create and invoice an intercompany purchase order for internal use](create-and-invoice-an-intercompany-purchase-order-for-internal-use.md), and [Create and invoice an intercompany sales order for internal use](create-and-invoice-an-intercompany-sales-order-for-internal-use.md).

You can create a purchase agreement or sales agreement for one of the intercompany trading parties. You can then generate the corresponding sales agreement or purchase agreement for the other intercompany trading party in the other legal entity.

If you create an intercompany purchase order that uses the intercompany purchase agreement in one legal entity, the corresponding intercompany sales order uses the corresponding intercompany sales agreement in the other legal entity. The fulfillment of the sales agreement commitments and the fulfillment of the purchase agreements are synchronized, just as the intercompany sales order and the intercompany purchase order are synchronized.

## Purchase agreement tranches and lots

You can create a hierarchy of purchase agreements. The master, high-level agreement is the parent, and each subsidiary, lower-level agreement functions as a child. Because the purchase agreement represents a marché, this parent-child hierarchy can be used to create tranches and lots.


> [!NOTE]
> <P>This functionality is available only if all three of the following conditions are true:</P>
> <UL>
> <LI>
> <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
> <LI>
> <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
> <LI>
> <P>The <STRONG>Use French public sector accounting rules</STRONG> check box in the <STRONG>Budget parameters</STRONG> form is selected.</P></LI></UL>
> <P>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P>
> <P>For more information, see <A href="fra-key-tasks-administer-purchase-agreements-public-sector.md">(FRA) Key tasks: Administer purchase agreements (Public sector)</A>.</P>



## Financial dimensions on purchase agreements

You can copy financial dimensions to document headers or to individual lines of a purchase agreement. You can change the dimensions in the agreement header or agreement line at any time, and the dimensions are then automatically copied to the release header or release line of release orders.

## See also

[Set up purchase or sales agreement functionality](set-up-purchase-or-sales-agreement-functionality.md)

[Create a purchase release order](create-a-purchase-release-order.md)

[View purchase or sales release order lines](view-purchase-or-sales-release-order-lines.md)

[View vendor invoice lines for a purchase agreement](view-vendor-invoice-lines-for-a-purchase-agreement.md)

[View history of confirmed purchase agreements](view-history-of-confirmed-purchase-agreements.md)

[Print the status of a purchase agreement](print-the-status-of-a-purchase-agreement.md)

  


