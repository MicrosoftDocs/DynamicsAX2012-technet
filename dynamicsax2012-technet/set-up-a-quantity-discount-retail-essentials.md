---
title: Set up a quantity discount (Retail essentials)
TOCTitle: Set up a quantity discount (Retail essentials)
ms:assetid: 4b88fa2c-a8f2-4296-a405-483714c4d24c
ms:mtpsurl: https://technet.microsoft.com/library/Dn716086(v=AX.60)
ms:contentKeyID: 62200349
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up a quantity discount (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up a quantity discount. A quantity discount is a discount that is given to customers when they purchase a particular quantity of a product.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



1.  Click **Retail essentials** \> **Merchandising** \> **Pricing and discounts** \> **Quantity discounts**.

2.  Click **New** to create a new quantity discount.
    

    > [!TIP]
    > <P>To create a new discount that resembles an existing discount, you can save time by clicking <STRONG>Copy from</STRONG>. All the settings and products are then copied from one discount to the other.</P>



3.  Enter an ID number and a name for the discount. If number sequences are set up, the discount ID is entered automatically.

4.  On the **General** FastTab, in the **Status** field, select **Enabled** or **Disabled** to enable or disable the discount.
    

    > [!NOTE]
    > <P>You can modify a quantity discount only if it has a status of <STRONG>Disabled</STRONG>.</P>



5.  Click **RBO store**, and then, in the **Price group** form, select the price group for the stores that the discount applies to. Close the **Price group** form.

6.  In the **Quantity discounts** form, in the **Discount code** field, enter a discount code.
    
    In the **Bar code** field, a bar code is automatically generated for the discount code. The discount is applied to a purchase only if this bar code is entered or scanned in the point of sale (POS) system.
    

    > [!NOTE]
    > <P>For promotions, if you enter a value in the <STRONG>Discount code</STRONG> field, the value that you enter is the discount code that is published to the customer. Leave this field blank to use number sequences and bar codes to automatically generate a discount code that is published to the customer.</P>



7.  On the **Details** FastTab, in the **Description** field, type a description of the quantity discount. Then, in the **Disclaimer** field, type any disclaimer that is required. This disclaimer is used when the discount is published through Retail essentials.

8.  On the **Price/discount** FastTab, in the **Discount type** field, select **Discount %** to calculate the discount prices as percentage discounts. To enter specific prices for quantities of the item, select **Unit price**.

9.  On the **Validation period** FastTab, select **Standard** to specify a start date and end date for the discount. To select a predefined discount period, select **Advanced**.
    
    For more information about how to set up discount periods, see [Set up discount periods (Retail essentials)](set-up-discount-periods-retail-essentials.md).

10. On the **Lines** FastTab, click **Add** to add a single product to the discount. To add multiple products, click **Add products**.

11. Click **Image** to add an image to the quantity discount line.

12. On the **Lines** FastTab click **Add all variants** to automatically add a line for each variant that is available for the selected product.

13. Click **Configuration**, and then, in the **Quantity discount configuration** form, in the **Minimum quantity** field, type the minimum quantity that the customer must buy to qualify for the discount.

14. In the **Disc. %** field, enter the amount or percentage of the discount per unit.
    
    The value that you enter in this field depends on the value that you select in the **Discount type** field on the **Price/discount** FastTab of the **Quantity discounts** form.

15. If you want the discount that is given to increase as the quantities that are purchased increase, click **New** to create another minimum quantity. Then enter the amount or percentage of the discount for that quantity.

16. On the **Line details** FastTab, in the **Description** field, type a description of the line that is selected on the **Lines** FastTab.

## See also

Setting up price adjustments and discounts (Retail Essentials)

  


