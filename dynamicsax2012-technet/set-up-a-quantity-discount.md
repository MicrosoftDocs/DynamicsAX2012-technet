---
title: Set up a quantity discount
TOCTitle: Set up a quantity discount
ms:assetid: ab35354c-7f65-49bb-9fc3-1dba1846032e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597202(v=AX.60)
ms:contentKeyID: 39519273
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a quantity discount 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to set up a quantity discount. A quantity discount is a discount that is given to customers when they purchase a particular quantity of a product. For example, you could set up a 20 percent discount for the purchase of two or more tennis rackets of a particular brand.

1.  Click **Retail** \> **Common** \> **Pricing and discounts** \> **Quantity discounts**.

2.  Click **New** to create a new quantity discount.
    

    > [!TIP]
    > <P>To create a new discount that resembles an existing discount, you can save time by clicking <STRONG>Copy from</STRONG>. All the settings and products are then copied from one discount to the other.</P>



3.  Enter a **Discount** ID number and a **Name** for the discount. If number sequences are set up, Microsoft Dynamics AX enters the ID number automatically.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the discount.
    

    > [!NOTE]
    > <P>You can modify a discount only if it has a status of <STRONG>Disabled</STRONG>.</P>



5.  Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R3, click **Price groups**, and then select one or more price groups that the discount applies to.
        

        > [!NOTE]
        > <P>If a channel, catalog, affiliation, or loyalty program is associated with the price group that you select, the discount applies to that channel, catalog, affiliation, or loyalty program.</P>

    
      - In earlier versions of AX 2012, on the **General** FastTab, in the **Price group** field, select the price group that the discount applies to.

6.  In the **Discount code** field, enter a discount code that is used to apply the discount to purchases. Leave this field blank if you do not want to use a code to apply this discount.

7.  Select the **Discount code required** check box to indicate that the discount code must be entered to apply the discount.

8.  On the **Details** FastTab, in the **Description** field, type a description of the quantity discount. Then, in the **Disclaimer** field, type any disclaimer that is required.

9.  On the **Price/discount** FastTab, in the **Discount type** field, select **Discount %** to calculate the discount prices as percentage discounts. Or, to enter specific prices for quantities of the item, select **Unit price**.

10. On the **Validation period** FastTab, select **Standard** to specify a start date and end date for the discount. To select a predefined discount period, select **Advanced**.
    
    For more information about how to set up discount periods, see [Set up discount periods](set-up-discount-periods.md).

11. On the **Lines** FastTab, click **Add** to add a single product to the discount. To add multiple products, click **Add products**.

12. Click **Image** to add an image to the discount line.

13. Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3, on the **Lines** FastTab, click **Add all variants** to automatically add a line for each variant that is available for the selected product.
    
      - Otherwise, on the **Lines** FastTab, click **Explode product** to automatically add a line for each variant that is available for the selected product.

14. Click **Configuration**, and then, in the **Minimum quantity** field, type the minimum quantity that the customer must buy to qualify for the discount.

15. In the **Unit price** or **Disc. %** field, enter the amount or percentage of the discount per unit.
    
    The value that you enter in this field is dependent on the value that you select in the **Discount type** field on the **Price/discount** FastTab.

16. If you want the discount that is given to increase as the quantities that are purchased increase, click **New** to create another minimum quantity. Then, enter the amount or percentage of the discount for that quantity.

17. On the **Line details** FastTab, in the **Description** field, type a description of the line that is selected on the **Lines** FastTab.

## See also

[About price adjustments and discounts](about-price-adjustments-and-discounts.md)

[Setting up retail channels](setting-up-retail-channels.md)

[Setting up retail product catalogs](setting-up-retail-product-catalogs.md)

[Setting up affiliations](setting-up-affiliations.md)

[Setting up loyalty programs](setting-up-loyalty-programs.md)

  


