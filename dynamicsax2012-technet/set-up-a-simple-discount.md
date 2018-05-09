---
title: Set up a simple discount
TOCTitle: Set up a simple discount
ms:assetid: 3d5f92e9-4445-499b-8f38-3ce947f8fb86
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497740(v=AX.60)
ms:contentKeyID: 62200056
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up a simple discount 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up a simple discount for products. A simple discount reduces the price of one or more products by a set percentage or amount. Simple discounts and price adjustments are similar; however, a discount is applied after the product’s price is calculated, whereas a price adjustment adjusts the sales price directly. Optionally, you can post the discounted amount separately from the net price, which enables the reporting of sales revenue before discounts.

1.  Click **Retail** \> **Common** \> **Pricing and discounts** \> **Discounts**.

2.  Click **New** to create a new discount.
    

    > [!TIP]
    > <P>To create a new discount that is similar to an existing discount, you can save time by clicking <STRONG>Copy from</STRONG>. All the settings and products are then copied from one discount to the other.</P>



3.  Enter a **Discount** identification (ID) number and a **Name** for the discount. If number sequences are set up, Microsoft Dynamics AX enters the ID number automatically.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the discount.
    

    > [!NOTE]
    > <P>Discounts can be edited only if they have a status of <STRONG>Disabled</STRONG>.</P>



5.  Depending on your version of Microsoft Dynamics AX, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R3: Click **Price groups**, and then select one or more price groups that the discount applies to.
        

        > [!NOTE]
        > <P>If a channel, catalog, affiliation, or loyalty program is associated with the price group that you select, the discount applies to that channel, catalog, affiliation, or loyalty program.</P>

    
      - In earlier versions of AX 2012: On the **General** FastTab, in the **Price group** field, select the price group that the discount applies to.

6.  In the **Discount code** field, enter a discount code that is used to apply the discount to purchases. Leave this field blank if you do not want to use a code to apply this discount.

7.  Select the **Discount code required** check box to indicate that the discount code must be entered to apply the discount.

8.  On the **Details** FastTab, in the **Description** field, type a description. In the **Disclaimer** field, type any disclaimer that is required.

9.  On the **Price/discount** FastTab, in the **Discount percentage** field, enter a default percentage price reduction that will apply to all the products that you add to the discount.
    
    You can change the percentage or change the percentage to an amount, for each line, when you add the products on the **Lines** FastTab later in this procedure.

10. On the **Validation period** FastTab, select **Standard** to specify a start date and end date, or select **Advanced** to select a predefined discount period.
    
    For more information about how to set up discount periods, see [Set up discount periods](set-up-discount-periods.md).

11. On the **Lines** FastTab, click **Add** to add a single product to the discount. To add multiple products, click **Add products**.

12. On each line, in the **Discount method** field, select one of the following methods. Specify a value in the corresponding column.
    
      - **Discount percentage** – A percentage is deducted from the price.
    
      - **Cash discount amount** – An amount is deducted from the price.
    
      - **Discount price** – A new price is used for the product.
    
      - **Discount price including tax** – A new price that includes sales tax is used.

13. Optional: On the **Lines** FastTab, click **Image** to add an image to the discount line.

14. Depending on your version of Microsoft Dynamics AX, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3: On the **Lines** FastTab, click **Add all variants** to automatically add a line for each variant that is available for the selected product.
    
      - In earlier versions of AX 2012: On the **Lines** FastTab, click **Explode product** to automatically add a line for each variant that is available for the selected product.

15. On the **Line details** FastTab, in the **Description** field, type a description of the discount that applies to the line that is selected on the **Lines** FastTab.

## See also

[About price adjustments and discounts](about-price-adjustments-and-discounts.md)

[Setting up retail channels](setting-up-retail-channels.md)

[Setting up retail product catalogs](setting-up-retail-product-catalogs.md)

[Setting up affiliations](setting-up-affiliations.md)

[Setting up loyalty programs](setting-up-loyalty-programs.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

