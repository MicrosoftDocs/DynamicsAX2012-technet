---
title: Set category-based prices
TOCTitle: Set category-based prices
ms:assetid: 1ceb6ed5-251e-4f8b-9eed-ff4bf2e070bd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497726(v=AX.60)
ms:contentKeyID: 62200040
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set category-based prices 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to manage the prices of many products at the same time by using price rules and price groups that affect entire categories of products. This is especially useful if your company has many retail products.

You can specify a markup, margin, or fixed amount for the products in one or more categories, and then generate a price/discount agreement journal for sales prices. You can also limit the selected products to specific price groups and vendors.

The results of the proposed changes are displayed as an unposted price/discount agreement journal so you can modify them before you make the changes final.

To set category-based prices, follow these steps:

1.  Click **Retail** \> **Periodic** \> **Category price rules**.

2.  In the **Category price rules** form, click **New** to create a price rule.

3.  In the **Account code** field, select **Group**, and then select a price group in the **Account selection** field.

4.  In the **Category** field, select a category at any level from one of the retail category hierarchies.

5.  To price only the products from a specific vendor, select a vendor in the **Vendor account** field.

6.  In the **Price rule** field, select which type of price change to use:
    
      - **Markup** – A percentage of the price basis is used to calculate the sales price.
        
        Example: A product that costs 10.00 and sells for 15.00 has a markup of 50 percent.
    
      - **Margin** – A percentage of the sales price that is used to calculate the amount of profit.
        
        Example: A product that costs 10.00 and sells for 15.00 has a margin of 33.3 percent.
    
      - **Fixed amount** – An amount added to the price basis that is used to calculate the sales price.
        
        Example: A product that costs 10.00 and sells for 15.00 has a fixed amount of 5.00.

7.  In the **Price basis** field, select the type of price to modify:
    
      - **Base cost** – The amount that the retailer paid to the supplier.
    
      - **Base price** – The sales price before trade agreements and price adjustments are applied.
    
      - **Current price** – The sales price after trade agreements and price adjustments are applied.

8.  In the **Amount / percent** field, enter a percentage or the amount of the price change.

9.  In the **Rounding version** field, select a rounding method.

10. To price for a specific unit of measure, select a unit in the **Unit** field. If this field is left blank, the product’s default unit of measure is used.

11. Click **Generate trade agreements**.

12. On the **Product selection** page of the **Generate trade agreements** form, select which items to price, and then click **Next \>**:
    
      - **All items** – Price all the products in the selected categories.
    
      - **Items without prices** – Price only the products that don’t have prices. You might select this option to price products that have recently been added to Microsoft Dynamics AX and that don’t yet have prices.

13. On the **Trade agreement options** page, select options for the trade agreements that will be created, and then click **Next \>**.

14. On the **Price summary** page, review the summary.

15. Select the **Run as a batch job** check box to use a batch job to generate the price/discount agreement journal at another time. You will still have to post the journal after it is generated.
    
    You might want to use a batch job if you’re updating lots of products, which could take a long time.

16. Click **Finish**.
    
    If you didn’t select the **Run as a batch job** check box, the proposed price changes are displayed in the **Journal lines, price/discount agreement** form.

17. Review the proposed price changes, make any modifications, and then click **Post**.

## See also

[About setting prices by using price groups](about-setting-prices-by-using-price-groups.md)

  


