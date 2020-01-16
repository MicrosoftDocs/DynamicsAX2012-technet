---
title: Perform a stock count
TOCTitle: Perform a stock count
ms:assetid: 3a78e76d-0c76-47c3-b6c5-9c043347e650
ms:mtpsurl: https://technet.microsoft.com/library/Hh352241(v=AX.60)
ms:contentKeyID: 36687866
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPRetailStockCountDetails
- EPRetailStockCountEdit
- EPRetailStockCountNew
- EPRetailStockCountListPage
audience: Application User
ms.search.region: Global
---

# Perform a stock count 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use Enterprise Portal for Microsoft Dynamics AX to perform stock counts from any computer that has Internet access. You do not have to use a point of sale (POS) register.

And, you can use Enterprise Portal to perform two kinds of stock counts:

  - **Unscheduled stock count** – These stock counts are initiated by a store, when the items that must be counted are not specified by the head office. Unscheduled counts are often used for informal counts or spot checks, as part of loss prevention measures.

  - **Scheduled stock count** – These stock counts are initiated by the head office, which specifies the items that must be counted. The head office creates a counting document and sends it to the store, where actual on-hand quantities of stock are entered into Enterprise Portal.

When the unscheduled or scheduled stock count is completed, the store sends the completed counting document back to the head office, where it is posted to inventory.

You can perform a stock count by using a scanner or by entering the item information manually. If necessary, you can suspend the stock count and resume it later.

You can also perform unscheduled stock counts in Microsoft Dynamics AX for Retail POS. For more information, see Retail POS Help.


> [!NOTE]
> <P>Before you can perform a stock count, make sure that a store inventory terminal, a worksheet mask, and a staff member who has store inventory access are set up. For more information, see Retail Headquarters Help.</P>



## Create a new unscheduled stock count

1.  Log on to your company’s Enterprise Portal webpage by using an account that has store inventory access.
    
    Enterprise Portal displays the **Home** page. The **Home** page displays the Role Center that has been assigned to you.

2.  Click the **Retail** tab, and then, under **Common**, click **Stock counts**.
    
    Enterprise Portal displays a list of stock counts.

3.  Click **New**, enter a description, and then click **Continue**.
    
    Enterprise Portal displays the **Stock count** form.

4.  In the **Reference number** field, type a reference number for the stock count.

5.  Follow one of these steps:
    
      - Scan an item.
    
      - In the **Item number** field, select an item number.

6.  If the item is a variant, select dimensions in the **Size**, **Color**, **Style**, and **Configuration** fields, as necessary.

7.  In the **Quantity** field, type the product's quantity.

8.  Click **Add**.

9.  Repeat steps 8 through 11 for each item to count.

10. When you have finished adding items to the stock count, click **Submit** to send the stock count to Retail Headquarters.

## Complete a scheduled stock count

1.  Log on to your company’s Enterprise Portal webpage with an account that has store inventory access.
    
    Enterprise Portal displays the **Home** page. The **Home** page displays the Role Center that has been assigned to you.

2.  Click the **Retail** tab, and then, under **Common**, click **Stock counts**.
    
    Enterprise Portal displays a list of stock counts.

3.  Double-click an existing stock count.
    
    Enterprise Portal displays the **Stock count** form.

4.  For each product to count, in the **Quantity** field, type the product's quantity.

5.  When you have finished counting, click **Submit** to send the stock count to Retail Headquarters.

## See also

[Receive a purchase order or transfer order](receive-a-purchase-order-or-transfer-order.md)

[Complete an outgoing transfer order](complete-an-outgoing-transfer-order.md)

  


