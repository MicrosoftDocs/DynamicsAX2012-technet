---
title: Set up a mix-and-match discount (Retail essentials)
TOCTitle: Set up a mix-and-match discount (Retail essentials)
ms:assetid: 87ada9dc-3411-4566-aea3-e78a27471cbd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736912(v=AX.60)
ms:contentKeyID: 62200389
ms.date: 11/13/2014
mtps_version: v=AX.60
---

# Set up a mix-and-match discount (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In Retail essentials, there are four types of discounts: simple discounts, mix-and-match discounts, quantity discounts, and threshold discounts. This topic explains how to set up a mix-and-match discount.

A mix-and-match discount gives customers a discount when they purchase a specific combination of products. For example, a customer purchases two boxes of tea and receives 50 percent off the price of a tea cup. Products and variants can be included in mix-and-match discounts.

If you want to create a new discount that resembles an existing discount, you can save time by copying the existing discount. All of the settings and products are then copied to the new discount.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



To set up mix-and-match discounts, follow these steps:

1.  Click **Retail essentials** \> **Merchandising** \> **Pricing and discounts** \> **Mix and match discounts**.

2.  Press CTRL+N or click **New** to create a new mix-and-match discount.

3.  Enter the ID number and the name of the discount. The discount ID is automatically set only if number sequences are set up.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the discount.
    

    > [!NOTE]
    > <P>Only mix-and-match discounts that have a status of <STRONG>Disabled</STRONG> can be modified.</P>



5.  Click **Price groups**, and then, in the **Price groups** form, select the price group for the stores that the discount applies to. Close the **Price groups** form.

6.  In the **Discount code** field, enter a discount code. This code is used to apply the discount offer to purchases in retail stores.
    
    In the **Bar code** field, a bar code is automatically generated for the discount code. This bar code must be entered or scanned in the point of sale (POS) system to apply the discount to the purchase.
    

    > [!NOTE]
    > <P>If you enter a value in the <STRONG>Discount code</STRONG> field, the value that you enter is the discount code that is published to the customer. Leave this field blank to use number sequences and bar codes to automatically generate a discount code that is published to the customer.</P>



7.  Select the **Discount code required** check box to indicate that the discount code must be entered to apply the discount. If you clear this check box, all the stores in the channel receive the discount.

8.  On the **Details** FastTab, in the **Description** field, type a description of the discount. Then, in the **Disclaimer** field, type any disclaimer that is required. This disclaimer is used when the discount is published through Sites Services for Microsoft Dynamics ERP.

9.  On the **Price/discount** FastTab, in the **Discount type** field, follow one of these steps:
    
      - Select **Deal price**. Then, in the **Deal price value** field, type the specific price of the discounted total. The **Deal price value** field is used for both tax-inclusive and tax-exclusive configurations. Depending on store settings, the price either includes or excludes tax.
    
      - Select **Discount %**. Then, in the **Discount % value** field, type the percentage of the discount. For example, the usual price of product A is 40.00, and the usual price of product B is 60.00. A mix-and-match discount of 30 percent applies to these products. Therefore, if a customer buys product A and product B together, the cost is 70.00 instead of 100.00.
    
      - Select **Discount amount**. Then, in the **Discount amount value** field, type the specific amount of the discount.
    
      - Select **Least expensive**. Then, in the **Number of least expensive lines** field, type the number of least-expensive products that are free.
    
      - Select **Line spec**. Then specify the discount or price per product.

10. On the **Validation period** FastTab, select **Standard** to specify a start date and end date for the discount. Alternatively, select **Advanced** to select a predefined discount period.
    
    Discount periods must already be set up. For more information about how to set up a discount period, see [Set up discount periods (Retail essentials)](set-up-discount-periods-retail-essentials.md).

11. Click **Mix and match line groups**, and then, in the **Mix and match line groups** form, select among the predefined line groups. Then, in the **Number of products needed** field, type the quantity of the product that the customer must purchase to qualify for the discount.

12. In the **Line color** field, select a color.
    

    > [!TIP]
    > <P>Select a different color for each line group, so that you can easily distinguish the various line groups at the point of sale.</P>



13. On the **Lines** FastTab, click **Add** to add a single category, product, or variant to the discount. Alternatively, click **Add products** to add multiple categories, products, or variants.

14. For each line that is added to the mix-and-match discount, if the product must be included in a line group, select the line group. Close the **Mix and match line groups** form.

15. In the **Mix and match discounts** form, on the **Lines** FastTab, click **Image** to add an image to the mix-and-match discount line if the mix-and-match discount line is published through Retail essentials.

16. Click **Add all variants** to automatically add a line for each variant that is available for the selected product.

17. On the **Line details** FastTab, in the **Description** field, type a description of the line that is selected on the **Lines** FastTab.

18. On the **General** FastTab, in the **Status** field, select **Enabled**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

