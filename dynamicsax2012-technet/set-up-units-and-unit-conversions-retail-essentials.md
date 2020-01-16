---
title: Set up units and unit conversions (Retail essentials)
TOCTitle: Set up units and unit conversions (Retail essentials)
ms:assetid: ee3b5eba-7b77-4d45-9523-731e21b696ac
ms:mtpsurl: https://technet.microsoft.com/library/Dn736971(v=AX.60)
ms:contentKeyID: 62200448
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up units and unit conversions (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up units of measure and unit conversions for products in Retail essentials. A unit of measure is a standard quantity, size, or other basis that is used for measurement or exchange. When you enter an order in Retail essentials, you specify a quantity and the unit of measure that the quantity represents. For example, you might enter an order for a quantity of 5 bolts, which have a unit measurement of pieces. You must define the units of measure to use for all of the products that you purchase and sell.

You can also set up conversion rules that control how units of measure are converted to different units of measure. For example, you might convert weight measurement units from pounds to kilograms. You can set up standard or product-specific rules for converting units of measure. If both a product-specific and a standard conversion rule exist for a unit of measure, the product-specific conversion rule is used to convert units of measure for the product.


> [!NOTE]
> <P>A conversion rule that is set up to, for example, convert minutes to days also covers the conversion from days to minutes. Each unit of measure can have multiple unit conversion associated with it.</P>



## Set up units of measure

Use the following steps to create a unit of measure.

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Units** \> **Units**.

2.  In the **Units** form, click **New** to create a unit of measure. To modify an existing unit, select it in the left pane.

3.  In the **Unit** field, enter a unique identifier for the unit of measure.

4.  In the **Description** field, enter a descriptive name of the unit of measure.

5.  If the **Fixed unit assignment** check box is selected, you can identify the unit of measure as one of the fixed units of measure that are listed in the **Fixed unit** field.

6.  In the **Fixed unit** field, select a unit of measure to associate with the current unit. By using this association, specific units of measure can be identified by the business logic in Retail essentials and conversions between the units of measure are completed automatically.

7.  In the **Unit class** field, select a class of measurement for the unit. The unit class represents a logical grouping of units of measure such as area, mass, or quantity.

8.  In the **System of units** field, select whether to use metric units.

9.  Complete the remaining information for the unit of measure. For more information, see [Units (form)](https://technet.microsoft.com/library/hh209233\(v=ax.60\))

## Set up unit conversions

Use the following steps to set up a conversion for units of measure.

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Units** \> **Unit conversions**.

2.  In the **Unit conversions** form, click **New** to create a new conversion rule. To modify an existing conversion, select it in the list.

3.  In the left pane, select the type of conversion to set up from the following options:
    
      - **Standard conversions** – Rules that apply for all products. Standard conversion rules can only be set up for units of measure in the same unit class.
    
      - **Intra-class conversions** – Rules for units of measure in the same unit class. For example, you can set up a conversion rule for a product that converts a box to the number of pieces in a box. Pieces and boxes are both assigned to the **Quantity** unit class.
    
      - **Inter-class conversions** - Rules for units of measure across unit classes. For example, you can set up a conversion rule for a product that converts kilograms to liters. Kilograms are assigned to the **Mass** unit class and liters are assigned to the **Liquid volume** unit class.

4.  In the **Factor** field, enter a conversion factor between the **From unit** and the **To unit**. For example, the conversion factor from centimeter to meter is 100 because there are 100 centimeters in one meter.

5.  With the numerator and the denominator values, you can indicate whether the relation between the **From unit** and the **To unit** is a 1:1 ratio or if it is a fraction.
    
    For example, you want to create a conversion rule for a product where only a half piece fits into a box. In this case you can set up a conversion factor with **From unit** = Box and **To unit** = Pieces, and then enter 1 in the **Numerator** field and 2 in the **Denominator** field.

6.  In the **Rounding** field, select the method for rounding a fractional value when the conversion rule is applied.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Unit conversions (form)](https://technet.microsoft.com/library/hh209285\(v=ax.60\))

  


