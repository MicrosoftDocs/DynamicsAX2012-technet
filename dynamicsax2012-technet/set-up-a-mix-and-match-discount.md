---
title: Set up a mix-and-match discount
TOCTitle: Set up a mix-and-match discount
ms:assetid: fe8ca38a-2536-4e40-94d5-5cacc031c8af
ms:mtpsurl: https://technet.microsoft.com/library/Hh597304(v=AX.60)
ms:contentKeyID: 39519393
author: tonyafehr
ms.date: 08/12/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a mix-and-match discount 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes how to set up mix-and-match discounts. A mix-and-match discount gives customers a discount when they purchase a specific combination of products. For example, a customer purchases two boxes of tea and receives 50 percent off the price of a tea cup. Products and variants can be included in mix-and-match discounts.

1.  Click **Retail** \> **Common** \> **Pricing and discounts** \> **Mix and match discounts**.

2.  Press CTRL+N or click **New** to create a new mix-and-match discount.
    

    > [!TIP]
    > <P>To create a new discount that resembles an existing discount, you can save time by clicking <STRONG>Copy from</STRONG>. All the settings and products are then copied from one discount to the other.</P>



3.  Enter a **Discount** ID number and a **Name** for the discount. If number sequences are set up, Microsoft Dynamics AX enters the ID number automatically.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the discount.
    

    > [!NOTE]
    > <P>You can modify a discount only if it has a status of <STRONG>Disabled</STRONG>.</P>



5.  Depending on your version of Microsoft Dynamics AX, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R3, click **Price groups**, and then select one or more price groups that the discount applies to.
        

        > [!NOTE]
        > <P>If a channel, catalog, affiliation, or loyalty program is associated with the price group that you select, the discount applies to that channel, catalog, affiliation, or loyalty program.</P>

    
      - In earlier versions of AX 2012, on the **General** FastTab, in the **Price group** field, select the price group that the discount applies to.

6.  In the **Discount code** field, enter a discount code that is used to apply the discount to purchases. Leave this field blank if you do not want to use a code to apply this discount.

7.  Select the **Discount code required** check box to indicate that the discount code must be entered to apply the discount.

8.  On the **Details** FastTab, in the **Description** field, type a description of the discount. Then, in the **Disclaimer** field, type any disclaimer that is required.

9.  On the **Price/discount** FastTab, in the **Discount type** field, follow one of these steps:
    
      - Select **Deal price**. Then, in the **Deal price value** field, type the specific price of the discounted total. The **Deal price value** field is used for both tax-inclusive and tax-exclusive configurations. Depending on store settings, the price either includes or excludes tax.
    
      - Select **Discount %**. Then, in the **Discount % value** field, type the percentage of the discount. For example, the usual price of product A is 40.00, and the usual price of product B is 60.00. A mix-and-match discount of 30 percent applies to these products. Therefore, if a customer buys product A and product B together, the cost is 70.00 instead of 100.00.
    
      - Select **Discount amount**. Then, in the **Discount amount value** field, type the specific amount of the discount.
    
      - Select **Least expensive**. Then, in the **Number of least expensive lines** field, type the number of least-expensive products that you want to apply the discount to, and then enter a value of the discount in one of the following fields:
        
          - **Deal price value**
        
          - **Discount % value**
        
          - **Discount amount value**
        
        Select **Line spec**. Then specify the discount or price per product.

10. On the **Validation period** FastTab, select **Standard** to specify a start date and end date for the discount. Alternatively, select **Advanced** to select a predefined discount period.
    
    Discount periods must already be set up. For more information about how to set up a discount period, see [Set up discount periods](set-up-discount-periods.md).

11. On the **Lines** FastTab, click **Add** to add a single category, product, or variant to the discount. Alternatively, click **Add products** to add multiple categories, products, or variants.

12. Click **Mix and match line groups**, and then select among the predefined line groups. Then, in the **Number of products needed** field, type the quantity of the product that the customer must purchase to qualify for the discount.

13. In the **Line color** field, select a color.
    

    > [!TIP]
    > <P>Select a different color for each line group, so that you can easily distinguish the various line groups at the point of sale.</P>



14. For each line that is added to the mix-and-match discount, select a **Line group**.

15. Click **Image** to add an image to the mix-and-match discount line.

16. Depending on your version of the program, do one of the following:
    
      - In AX 2012 R2 and AX 2012 R3, on the **Lines** FastTab, click **Add all variants** to automatically add a line for each variant that is available for the selected product.
    
      - In earlier versions of AX 2012, on the **Lines** FastTab, click **Explode product** to automatically add a line for each variant that is available for the selected product.

17. On the **Line details** FastTab, in the **Description** field, type a description of the line that is selected on the **Lines** FastTab.

## See also

[About price adjustments and discounts](about-price-adjustments-and-discounts.md)

[Setting up retail channels](setting-up-retail-channels.md)

[Setting up retail product catalogs](setting-up-retail-product-catalogs.md)

[Setting up affiliations](setting-up-affiliations.md)

[Setting up loyalty programs](setting-up-loyalty-programs.md)

  


