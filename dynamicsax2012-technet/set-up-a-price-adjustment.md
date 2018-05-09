---
title: Set up a price adjustment
TOCTitle: Set up a price adjustment
ms:assetid: a65ebb2b-352c-4875-a997-718595ca3864
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597199(v=AX.60)
ms:contentKeyID: 39519268
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- discounts
- discount
- price adjustment
- price adjustments
---

# Set up a price adjustment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes how to use price adjustments to reduce the price of one or more products by a set percentage or amount. Price adjustments and simple discounts are similar. However, a discount is applied after the product’s price is calculated, while a price adjustment adjusts the sales price directly. You can optionally choose to post the discounted amount separately from the net price, which allows you to report sales revenue before discounts.

1.  Click **Retail** \> **Common** \> **Pricing and discounts** \> **Price adjustments**.

2.  Click **New** to create a new price adjustment.
    

    > [!TIP]
    > <P>To create a new price adjustment that resembles an existing price adjustment, you can save time by clicking <STRONG>Copy from</STRONG>. All the settings and products are then copied from one price adjustment to the other.</P>



3.  Enter a discount ID number and a name for the price adjustment. If number sequences are set up, the ID number is entered automatically.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the price adjustment.
    

    > [!NOTE]
    > <P>Price adjustment can be edited only if they have a status of <STRONG>Disabled</STRONG>.</P>



5.  Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R3, click **Price groups**, and then select one or more price groups that the price adjustment applies to.
        

        > [!NOTE]
        > <P>If a channel, catalog, affiliation, or loyalty program is associated with the price group that you select, the price adjustment applies to that channel, catalog, affiliation, or loyalty program.</P>

    
      - In earlier versions of AX 2012, on the **General** FastTab, in the **Price group** field, select the price group that the price adjustment applies to.

6.  On the **Details** FastTab, in the **Description** field, type a description. Then, in the **Disclaimer** field, type any disclaimer that is required.

7.  On the **Price/discount** FastTab, in the **Discount percentage** field, enter a price reduction as a percentage that will apply to all the products that you add to the price adjustment.
    
    You can change the percentage, or you can change the percentage to an amount, for each line, when you add the products on the **Lines** FastTab later in this procedure.

8.  On the **Validation period** FastTab, select **Standard** to specify a start date and end date, or select **Advanced** to select a predefined discount period.
    
    For more information about how to set up discount periods, see [Set up discount periods](set-up-discount-periods.md).

9.  On the **Lines** FastTab, click **Add** to add a single product to the price adjustment. To add multiple products, click **Add products**.

10. On each line, in the **Discount method** field, select one of the following methods. Then specify a value in the corresponding column.
    
      - **Discount percentage** – A percentage is deducted from the price.
    
      - **Cash discount amount** – An amount is deducted from the price.
    
      - **Discount price** – A new price is used for the product.
    
      - **Discount price including tax** – A new price that includes sales tax is used.

11. On the **Lines** FastTab, click **Image** to add an image to the price adjustment line.

12. Depending on your version of the program, do one of the following:
    
      - In AX 2012 R2 and AX 2012 R3: On the **Lines** FastTab, click **Add all variants** to automatically add a line for each variant that is available for the selected product.
    
      - In earlier versions of AX 2012, on the **Lines** FastTab, click **Explode product** to automatically add a line for each variant that is available for the selected product.

13. On the **Line details** FastTab, in the **Description** field, type a description of the price adjustment that applies to the line that is selected on the **Lines** FastTab.

## See also

[About price adjustments and discounts](about-price-adjustments-and-discounts.md)

[Setting up retail channels](setting-up-retail-channels.md)

[Setting up retail product catalogs](setting-up-retail-product-catalogs.md)

[Setting up affiliations](setting-up-affiliations.md)

[Setting up loyalty programs](setting-up-loyalty-programs.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

