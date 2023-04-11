---
title: Calculations for product configuration models
TOCTitle: Calculations for product configuration models
ms:assetid: bc35311d-29a5-4501-a02d-7c022c2a1132
ms:mtpsurl: https://technet.microsoft.com/library/Dn283316(v=AX.60)
ms:contentKeyID: 54916489
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Calculations for product configuration models 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes calculations for product configuration models and how to use calculations together with constraints. You can define calculations in the **Constraint-based product configuration model details** form and then build expressions for the calculations in the expression editor. For more information, see [Create calculations](create-calculations.md).

## What is a calculation?

A calculation is an element that you can use in a configuration model. Calculations complement constraints by enabling you to calculate values by using decimal numbers when you configure a product. Furthermore, calculations have a larger set of operators available than constraints do. Like a constraint, a calculation is associated with a specific component in a product configuration model and it can’t be reused by or shared with another component. For more information about constraints, see [Expression constraints and table constraints](expression-constraints-and-table-constraints.md).

A calculation consists of a target attribute and a calculation expression.

## What is a target attribute?

A target attribute is an attribute that receives the result of the calculation in an expression.

In the following expression, the target attribute is a tablecloth measurement:

Expression: If\[(decimalAttribute1 / decimalAttribute2) \< 1, True, False\]

DecimalAttribute1 is the table length and decimalAttribute2 is the tablecloth length. The expression returns the value “True” to the target attribute if decimalAttribute2 is greater than or equal to decimalAttribute1, and “False” if it’s not. So the tablecloth measurement is acceptable if the tablecloth length is equal to or exceeds the length of the table.

## What attribute types can be set to target attributes?

All attribute types that are supported for the product configurator can be set to target attributes except for text without a fixed list.

## Can a value for the target restrict the values for the input attributes in a calculation?

No, the value for a target can’t restrict the values for the input attributes. Calculations are unidirectional. The value of the target attribute is set based on changes to the value of the input attributes. However, changing the value of the target doesn’t impact the value of the input attributes. This is contrary to how constraints work. In constraints, the calculation occurs in both directions.

**Example**

In the following expression, the target for the calculation is the length of a power cord and the input value is a color. If you select the input value Green as the color of the power cord, the length is set to 1.5. For other colors, the length is 1.0.

Expression: \[If Color == “Green”, 1.5, 1.0\]

When you configure the item, the calculation generates 1.5 as the length of the power cord if you specify Green as the color attribute. If you specify any other color, the length is 1.0. However, because calculations are unidirectional, the calculation does not set the value of the color attribute to Green when you specify a length of 1.5.

## What happens if a calculation has a target attribute of the integer type and a calculation gives you a decimal number?

The result of the calculation returns only the integer part of the calculation. The decimal part is removed and the result is not rounded. For example, the result of 12.70 is shown as 12.

## When do calculations occur?

Calculations occur when a value has been provided for all input attributes.

## Can I overwrite the value that is calculated for the target attribute?

You can overwrite the value that is calculated for the target attribute unless the target attribute is set as hidden or read-only.

## How do I set a target attribute as hidden or read-only?

To set an attribute as hidden or read-only, follow these steps:

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select a product configuration model. On the **Action Pane**, click **Edit**.

3.  In the **Constraint-based product configuration model details** form, select the attribute to use as a target attribute.

4.  On the **Attributes** FastTab, select **Hidden** or **Read-only**.

## Can a calculation overwrite the values I set?

No. The values that you set when you configure a product are the values that are used. The calculation that occurs when the input values in a calculation are changed can’t overwrite the values that you provide for a specific attribute.

## What happens if I remove an input value in a calculation?

If you remove an input value in a calculation, the value of the target attribute is also removed.

## Why do I get an error message that says my model is in contradiction?

This message is displayed when a calculation includes an error or a contradiction exists in one or more constraints. For more information about contradictions in constraints, see [Expression constraints and table constraints](expression-constraints-and-table-constraints.md). Errors in calculations can, for example, occur in the following situations:

  - A value is divided by zero.

  - A conflict exists between these two elements:
    
      - The values that are available for an attribute and that are limited by a constraint.
    
      - A value that is generated by a calculation.

  - The values that are returned by the calculation are outside the domain of the attribute. An example is an integer from \[1..10\] that is calculated to 0.

## Why do I get an error even though I successfully validated my product model?

Calculations are not included in the validation. You must test the product configuration model to find errors in calculations.

The following steps explain how to test a product configuration model:

  - Click **Product information management** \> **Common** \> **Product configuration models**.

  - Select a product configuration model. On the **Action Pane**, in the **Run** group, click **Test**.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


