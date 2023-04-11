---
title: Set up a threshold discount
TOCTitle: Set up a threshold discount
ms:assetid: dfa656a4-a334-4fcd-90f7-33f4a4f75f26
ms:mtpsurl: https://technet.microsoft.com/library/Dn497839(v=AX.60)
ms:contentKeyID: 62200171
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailPeriodicDiscount
audience: Application User
ms.search.region: Global
---

# Set up a threshold discount 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create a threshold discount, also called an amount-based discount. A threshold discount is a discount that is given to customers when the total for a transaction reaches one or more specified amounts. For example, you could create a discount that gives a 10 percent discount for purchases over 100.00 and a flat 25.00 discount for totals over 200.00.

1.  Click **Retail** \> **Common** \> **Pricing and discounts** \> **Threshold discounts**.

2.  Click **New** to create a new threshold discount.
    

    > [!TIP]
    > <P>To create a new discount that is similar to an existing discount, you can save time by clicking <STRONG>Copy from</STRONG>. All the settings and products are then copied from one discount to the other.</P>



3.  Enter a **Discount** identification (ID) number and a **Name** for the discount. If number sequences are set up, Microsoft Dynamics AX enters the ID automatically.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the discount.
    

    > [!NOTE]
    > <P>You can modify a discount only if it has a status of <STRONG>Disabled</STRONG>.</P>



5.  Click **Price groups**, and then select one or more price groups that the discount applies to.
    

    > [!NOTE]
    > <P>If a channel, catalog, affiliation, or loyalty program is associated with the price group that you select, the discount applies to that channel, catalog, affiliation, or loyalty program.</P>



6.  On the **General** FastTab, in the **Discount code** field, enter a discount code that is used to apply the discount to purchases. Leave this field blank if you do not want to use a code to apply this discount.

7.  Select the **Discount code required** check box to indicate that the discount code must be entered to apply the discount.

8.  On the **Details** FastTab, in the **Description** field, type a description of the discount. In the **Disclaimer** field, type any disclaimer that is required.

9.  On the **Price/discount** FastTab, select the **Count non-discountable items toward threshold** check box to include any non-discountable products on a transaction when calculating the discount.

10. On the **Threshold discount tiers** FastTab, create one or more thresholds to trigger the discount.
    
    For each threshold, click **Add**, enter an **Amount**, select a **Discount method**, and then enter a **Discount value**, either an amount or a percentage.
    
    For example, you could create one tier to give a 15 percent discount for transaction totals over $200.00 and another tier to replace the 15 percent discount with a flat $75.00 discount for any purchase over $500.00.

11. On the **Validation period** FastTab, select **Standard** to specify a start date and end date for the discount. To select a predefined discount period, select **Advanced**. For more information about how to set up discount periods, see [Set up discount periods](set-up-discount-periods.md).

12. On the **Lines** FastTab, click **Add** to add a single product to the discount. To add multiple products, click **Add products**.

13. Optional: Click **Image** to add an image to the discount line.

14. Click **Add all variants** to automatically add a line for each variant that is available for the selected product.

15. On the **Line details** FastTab, in the **Description** field, type a description of the line that is selected on the **Lines** FastTab.

## See also

[About price adjustments and discounts](about-price-adjustments-and-discounts.md)

[Setting up retail channels](setting-up-retail-channels.md)

[Setting up retail product catalogs](setting-up-retail-product-catalogs.md)

[Setting up affiliations](setting-up-affiliations.md)

[Setting up loyalty programs](setting-up-loyalty-programs.md)

  


