---
title: Define sales prices for products
TOCTitle: Define sales prices for products
ms:assetid: 2d85dac8-5091-44c2-8b3f-a869390fb76d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh802994(v=AX.60)
ms:contentKeyID: 44080966
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase prices per product variant
- sales prices per product variant
- set up prices for items
---

# Define sales prices for products [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By using trade agreements, you can specify price adjustments and discounts for one or more released products. You can also create trade agreement setups that specify individual prices for released product variants.


> [!NOTE]
> <P>The search for sales prices and discounts must be enabled before you can use trade agreements. To enable the search for sales prices and discounts, select the relevant options in the <STRONG>Activate price/discount</STRONG> forms. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa575310(v=ax.60)">Activate sales price/discount (form)</A>.</P>



## Base price and price adjustments

You can set up a base sales price and price update information on the **Sell** FastTab in the **Released product details** form. A base price that is set up directly on a product is adjusted by any price information that can be derived from a trade agreement. The base price can be set up for each product and for each product master. Before you can specify price variations for product variants, a trade agreement must be associated with the product master.

## Prices that are retrieved for product variants on a sales order line

When a product variant is specified on a sales order line, a price is retrieved from the base price information for the product master, and from trade agreement adjustments.

A trade agreement can be set up for specific inventory dimensions. When you enter a product variant on a sales order line, the base price is adjusted by any trade agreement lines that match the inventory dimensions of the product variant.


> [!NOTE]
> <P>An inventory dimension must be enabled for the price search to be included in the search when price adjustments are retrieved for product variants.</P>
> <P>To enable an inventory dimension for the price search, select the <STRONG>For purchase prices</STRONG> and <STRONG>For sales prices</STRONG> check boxes for the relevant dimensions in the <STRONG>Product dimension groups</STRONG>, <STRONG>Storage dimension groups</STRONG>, and <STRONG>Tracking dimension groups</STRONG> forms.</P>



## Create a trade agreement for a product

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, on the **Sell** tab, in the **Trade agreements** group, click **Create trade agreements** to create a trade agreement.

3.  Click **New** to create a trade agreement. In the **Name** field, select a price adjustment journal name or a discount journal name.

4.  Click **Lines** to create lines for the price adjustment or discount.

5.  Select **Price (sales)** in the **Relation** field, select **Table** in the **Item code** field, and select the product in the **Item relation** field.

6.  In the **Amount in currency** field, enter the price or the discount amount.

7.  Click **Post** to post the sales agreement lines.

## Create a trade agreement for product variants

1.  Complete steps 1 through 4 of the previous procedure.

2.  In the **Item relation** field, select the product master of the product variants.

3.  In the **Size**, **Color**, and **Configuration** fields, select the product dimensions that define the product variant.
    

    > [!TIP]
    > <P>For more information about how create product variants based on dimensions, see “Define a product master” in <A href="key-tasks-define-products.md">Key tasks: Define products</A>.</P>



## See also

[Activate sales price/discount (form)](https://technet.microsoft.com/en-us/library/aa575310\(v=ax.60\))

[Product dimension groups (form)](https://technet.microsoft.com/en-us/library/hh227672\(v=ax.60\))

[Storage dimension groups (form)](https://technet.microsoft.com/en-us/library/hh209317\(v=ax.60\))

[Tracking dimension groups (form)](https://technet.microsoft.com/en-us/library/hh209465\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

