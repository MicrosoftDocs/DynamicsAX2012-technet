---
title: Create an expression constraint for a product component
TOCTitle: Create an expression constraint for a product component
ms:assetid: db0d0243-b5a7-41fc-9e9c-0690d713b29b
ms:mtpsurl: https://technet.microsoft.com/library/Hh597257(v=AX.60)
ms:contentKeyID: 39519336
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product configurator
- expression constraint
audience: Application User
ms.search.region: Global
---

# Create an expression constraint for a product component 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes how to create expression constraints for components in a product configuration model in Microsoft Dynamics AX. Constraints control the attribute values that are available for components when you configure a product for a sales quotation, purchase order, or production order. You can use the following types of constraints:

  - Expression constraints

  - Table constraints

Table constraints and expression constraints differ in the way the constraints are built. However, the type of constraint that is used has no impact on how you actually configure a product. For more information about the difference between the types of constraints, see [Expression constraints and table constraints](expression-constraints-and-table-constraints.md).

For more information about how to create table constraints, see [Create a table constraint](create-a-table-constraint.md).

## Create an expression constraint

Expression constraints are characterized by an expression that uses arithmetic and Boolean operators and functions. An expression constraint is written for a specific component in a product configuration model. It cannot be reused by or shared with another component. However, the expression constraints for a component can reference attributes of the component's subcomponents. You use constraints to control the attribute values that you can use when you configure products for a sales order, sales quotation, purchase order, or production order.

You can use the expression editor to create expression constraints, or you can just write them by using OML syntax for the attributes. Use Microsoft Solver Foundation constraint solver to solve the constraints. You must use Optimization Modeling Language (OML) syntax when you write the constraints. For more information, see [Microsoft Solver Foundation](https://go.microsoft.com/fwlink/?linkid=217059).

Follow these steps to create an expression constraint using the expression editor:

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  In the component tree, select the component to write an expression constraint for.

3.  Select a product configuration model, and then click **Edit**.

4.  In the **Constraint-based product configuration model details** form, on the **Constraints** FastTab, click **Add** to add a new constraint.

5.  In the **Constraint type** field, select **Expression constraint**, and then click **Create**.

6.  In the **Expression** field, click the drop-down arrow or press Alt, Down Arrow.

7.  In the **Expression constraint editor** form, on the **All symbols** tab, double-click a symbol or press Enter to enter the symbol in the **Expression** field.

8.  Use the same method to add attributes, operators, and values to the expression. For more information about the use of attributes, operators, and values, see [Expression constraints and table constraints](expression-constraints-and-table-constraints.md).

9.  Click **Validate** to validate the constraint, and then click **OK** to close the **Expression constraint editor** form.

Follow these steps to create an expression constraint without using the expression editor:

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  In the component tree, select the component to write an expression constraint for.

3.  Select a product configuration model, and then click **Edit**.

4.  In the **Constraint-based product configuration model details** form, on the **Constraints** FastTab, click **Add** to add a new constraint.

5.  In the **Constraint type** field, select **Expression constraint**, and then click **Create**.

6.  In the **Expression** field, write the expression. Make sure that the attributes that you write comply with the OML syntax that is defined for the attribute types. See the table in the next section for an example of how attributes are written by using OML syntax.

7.  Click **Validate** to validate the constraint.

## Example of an expression constraint

This example shows how you can limit the configuration of a television to specific sizes and types for a seasonal offer.

A projection television must have a screen size that is larger than or equal to 50 inches, either two or four USB ports, and a black frame. The following attribute types are created in the product configuration model. The solver name is the name of the attribute type written by using OML syntax.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Solver name</p></th>
<th><p>Type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Screen Type</p></td>
<td><p>screenType</p></td>
<td><p>Integer with a range</p></td>
</tr>
<tr class="even">
<td><p>USB Ports</p></td>
<td><p>usbPorts</p></td>
<td><p>Text with a fixed list</p></td>
</tr>
<tr class="odd">
<td><p>Frame Color</p></td>
<td><p>frameColor</p></td>
<td><p>Text with a fixed list</p></td>
</tr>
</tbody>
</table>


The expression looks like this:

screenType == “Projection” -: (screenSize \>= 50

(& usbPorts == “two” | usbPorts == “four”)

& frameColor == “black”)

This expression constraint uses the Implies operator, -:, and it has the following two parts:

  - The part on the left side of the implication operator accesses the screenType attribute and it evaluates to “True” if the screen type gets the “Projection” value.

  - The part on the right side of the implication operator is a conjunction of Boolean expressions that ensures the following:
    
      - The screenSize attribute is larger than or equal to 50 inches.
    
      - The number of USB ports is either two or four.
    
      - The color is black.

This conjunction evaluates to “True” if all the inner expressions are satisfied. If the complete expression is considered, an implication such as “A -: B” is satisfied if:

  - A evaluates to “True.” Then B must be “True.”

  - A evaluates to “False.” Then B can evaluate to “True” or “False.”

Because this is a constraint and not a rule, the Solver Engine doesn’t wait for a change on the right-side expression before it evaluates the expression. Instead, the Solver Engine makes sure that the expression is always satisfied. In this example, if the television attributes do not satisfy the Boolean expression, the television cannot be a projection television.

## Related tasks

[Create a table constraint](create-a-table-constraint.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is needed for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To use the expression editor, you must be a member of the Product designer (BOMProductDesigner) security role.</p></td>
</tr>
</tbody>
</table>


## See also

[About product configuration models](about-product-configuration-models.md)

[About system-defined and user-defined table constraints](about-system-defined-and-user-defined-table-constraints.md)

[Expression constraints and table constraints](expression-constraints-and-table-constraints.md)

  


