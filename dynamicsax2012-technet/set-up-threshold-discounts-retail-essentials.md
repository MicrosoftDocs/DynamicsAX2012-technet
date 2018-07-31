---
title: Set up threshold discounts (Retail essentials)
TOCTitle: Set up threshold discounts (Retail essentials)
ms:assetid: 42deb655-9070-43ad-a259-38e8890f61f9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn859562(v=AX.60)
ms:contentKeyID: 63820136
ms.date: 01/14/2015
mtps_version: v=AX.60
---

# Set up threshold discounts (Retail essentials) 


This topic explains how to create a threshold discount, which is also referred to as an amount-based discount. A threshold discount is a discount that is given to customers when the total for a transaction reaches one or more specified amounts. For example, you can create a discount that gives a 10 percent discount for purchases over 100.00 and a flat 25.00 discount for totals over 200.00.

1.  Click **Retail essentials** \> **Merchandising** \> **Pricing and discounts** \> **Threshold discounts**.

2.  Click **New** to create a new threshold discount.
    

    > [!TIP]
    > <P>To create a new discount that resembles an existing discount, you can save time by clicking <STRONG>Copy from</STRONG>. All the settings and products are then copied from one discount to the other.</P>



3.  In the **Discount** field, enter an identification (ID) number for the discount. In the **Name** field, enter a name for the discount. If number sequences are set up, Microsoft Dynamics AX enters the ID number automatically.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the discount.
    

    > [!NOTE]
    > <P>You can modify a discount only if it has a status of <STRONG>Disabled</STRONG>.</P>



5.  Click **Price groups**, and then select one or more price groups that the discount applies to.
    

    > [!NOTE]
    > <P>If a channel, catalog, affiliation, or loyalty program is associated with the price group that you select, the discount applies to that channel, catalog, affiliation, or loyalty program.</P>



6.  On the **General** FastTab, in the **Discount code** field, enter a discount code that is used to apply the discount to purchases. If you do not want to use a code to apply this discount, leave the field blank.

7.  Select the **Discount code required** check box to indicate that the discount code must be entered to apply the discount.

8.  On the **Details** FastTab, in the **Description** field, enter a description of the discount. In the **Disclaimer** field, enter any disclaimer that is required.

9.  On the **Price/discount** FastTab, select the **Count non-discountable items toward threshold** check box to include any non-discountable products on a transaction when the discount is calculated.

10. On the **Threshold discount tiers** FastTab, create one or more thresholds to trigger the discount.
    
    For each threshold, click **Add**, enter an amount, select a discount method, and then enter a discount value. The discount value can be either an amount or a percentage.
    
    For example, you can create one tier to give a 15 percent discount for transaction totals over $200.00. You can then create another tier to replace the 15 percent discount with a flat $75.00 discount for any purchase over $500.00.

11. On the **Validation period** FastTab, select **Standard** to specify a start date and end date for the discount. To select a predefined discount period, select **Advanced**. For more information about how to set up discount periods, see [Set up discount periods (Retail essentials)](set-up-discount-periods-retail-essentials.md).

12. On the **Lines** FastTab, click **Add** to add a single product to the discount. To add multiple products, click **Add products**.

13. Optional: Click **Image** to add an image to the discount line.

14. Click **Add all variants** to automatically add a line for each variant that is available for the selected product.

15. On the **Line details** FastTab, in the **Description** field, enter a description of the line that is selected on the **Lines** FastTab.

## See also

[Setting up retail stores (Retail essentials)](setting-up-retail-stores-retail-essentials.md)

[Set up affiliations (Retail essentials)](set-up-affiliations-retail-essentials.md)

[Loyalty programs (Retail essentials)](loyalty-programs-retail-essentials.md)

  


