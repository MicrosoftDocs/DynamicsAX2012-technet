---
title: Set up a price adjustment or discount (Retail essentials)
TOCTitle: Set up a price adjustment or discount (Retail essentials)
ms:assetid: dceb8286-54fc-4e1a-9d1e-e29c18520c3e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736966(v=AX.60)
ms:contentKeyID: 62200443
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up a price adjustment or discount (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In Retail essentials, the processes for setting up price adjustments and setting up discounts are similar. You can use this procedure for both price adjustments and discounts, because most of the same options and settings apply to both. This topic explains how to set up price adjustments and discounts.

If you want to create a new discount that resembles an existing discount, you can save time by copying the existing discount. All the settings and products are then copied from the original discount.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



To set up price adjustments and discounts, follow these steps:

1.  Click **Retail essentials** \> **Merchandising** \> **Pricing and discounts** \> **Price adjustments**.
    
    –or–
    
    Click **Retail essentials** \> **Merchandising** \> **Pricing and discounts** \> **Discounts**.

2.  Click **New** to create a new price adjustment or discount.

3.  Enter the ID number and the name of the price adjustment or discount. The ID number is automatically set only if number sequences are set up.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the price adjustment or discount.
    

    > [!NOTE]
    > <P>Only price adjustments and discounts that have a status of <STRONG>Disabled</STRONG> can be modified.</P>



5.  Click **Price groups**, and then, in the **Price groups** form, in the **Price group** field, select the price group for the stores that the price adjustment or discount applies to. Close the **Price groups** form.

6.  If you are setting up a discount, in the **Discount code** field, enter a discount code. This code is used to apply the discount offer to purchases. The discount code can be used for promotions in retail stores.
    

    > [!NOTE]
    > <UL>
    > <LI>
    > <P>The <STRONG>Discount code</STRONG> field does not apply to price adjustments.</P>
    > <LI>
    > <P>For promotions, if you enter a value in the <STRONG>Discount code</STRONG> field, the value that you enter is the discount code that is published to the customer. Leave this field blank to use number sequences and bar codes to automatically generate a discount code that is published to the customer.</P></LI></UL>

    
    In the **Bar code** field, a bar code is automatically generated for the discount code. This bar code must be entered or scanned in the point of sale (POS) system to apply the discount to the purchase.

7.  If you are setting up a discount, select the **Discount code required** check box to indicate that the discount code must be entered to apply the discount.

8.  On the **Details** FastTab, in the **Description** field, type a description. Then, in the **Disclaimer** field, type any disclaimer that is required. This disclaimer is used when the price adjustment or discount is published through Retail essentials.

9.  On the **Price/discount** FastTab, in the **Discount percentage** field, type the percentage of the price reduction. This value is used as a template when new lines are added.

10. On the **Validation period** FastTab, select **Standard** to specify a start date and end date, or select **Advanced** to select a predefined discount period.
    
    For more information about how to set up discount periods, see [Set up discount periods (Retail essentials)](set-up-discount-periods-retail-essentials.md).

11. On the **Lines** FastTab, click **Add** to add a single product to the price adjustment or discount. To add multiple products, click **Add products**.

12. On each line, in the **Discount method** field, select one of the following methods. Then specify a value in the corresponding column.
    
      - **Discount percentage** – A percentage is deducted from the price of the product.
        

        > [!NOTE]
        > <P>The <STRONG>Discount percentage</STRONG> option does not apply to price adjustments.</P>

    
      - **Cash discount amount** – An amount is deducted from the price of the product.
    
      - **Discount price** – A new price is used for the product.
    
      - **Discount price including tax** – A new price that includes sales tax is used for the product.

13. On the **Lines** FastTab, click **Image** to add an image to the price adjustment or discount line if the price adjustment or discount lines are published through Sites Services for Microsoft Dynamics ERP.

14. On the **Lines** FastTab, click **Add all variants** to automatically add a line for each variant that is available for the selected product.

15. On the **Line details** FastTab, in the **Description** field, type a description of the price adjustment or discount that applies to the line that is selected on the **Lines** FastTab.

## See also

Setting up price adjustments and discounts (Retail Essentials)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

