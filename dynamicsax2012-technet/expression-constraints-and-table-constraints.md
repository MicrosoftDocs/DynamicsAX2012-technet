---
title: Expression constraints and table constraints
TOCTitle: Expression constraints and table constraints
ms:assetid: e1a7370d-890e-4ba5-bb62-5c4b01c0e40f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn283317(v=AX.60)
ms:contentKeyID: 54916491
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Expression constraints and table constraints [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes the use of expression constraints and table constraints. Constraints control the attribute values that you can select when you configure products for a sales order, sales quotation, purchase order, or production order. You can use expression constraints or table constraints, depending on how you prefer to build the constraints.

## What are expression constraints?

Expression constraints are characterized by an expression that uses arithmetic and Boolean operators and functions. An expression constraint is written for a specific component in a product configuration model. It can't be reused by or shared with another component. However, the expression constraints for a component can reference attributes of the component's subcomponents. For information about how to create an expression constraint, see [Create an expression constraint for a product component](create-an-expression-constraint-for-a-product-component.md).

## What are table constraints?

Table constraints list the combinations of values that are allowed for attributes when you configure a product. Table constraint definitions can be used generically. When you create a table constraint for a component in a product configuration model, you select a table constraint definition.

To create the combinations that are allowed, you add attributes of specific types to the components. Each attribute type has a specific value. For information about how to create a table constraint and how to add it to a product configuration model, see [Create a table constraint](create-a-table-constraint.md) and [Add a table constraint to a component](add-a-table-constraint-to-a-component.md).

**Example of a table constraint**

This example shows how you can limit the configuration of a television to specific sizes and types for a seasonal offer.

This first table shows the sizes and types of televisions that are generally available for configuration. The television sizes and types are the values that are available for the **TelevisionType** and **TelevisionSize** attribute types.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Attribute
  </p> </th>
    <th> <p>
   
	 Attribute type
  </p> </th>
    <th> <p>
   
	 Values
  </p> </th>
  </tr>
  <tr>
    <td rowspan="2"> <p>
   
	 Television
  </p> </td>
    <td> <p>
   
	 TelevisionSize
  </p> </td>
    <td> <p>
   
	 24, 36, 42, 48, 50
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 TelevisionType
  </p> </td>
    <td> <p>
   
	 Plasma, Projection, OLED, LCD
  </p> </td>
  </tr>
</table>


This next table shows the combinations that are defined by the **TV seasonal offer** table constraint. By using this table constraint, you can configure a Plasma television and a Projection television only in sizes 48 and 50, and you can configure an LCD television only in size 36.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Table constraint
  </p> </th>
    <th> <p>
   
	 Type
  </p> </th>
    <th> <p>
   
	 Size
  </p> </th>
  </tr>
  <tr>
    <td rowspan="5"> <p>
   
	 TV seasonal offer
  </p> </td>
    <td> <p>
   
	 Plasma
  </p> </td>
    <td> <p>
   
	 48
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Plasma
  </p> </td>
    <td> <p>
   
	 50
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Projection
  </p> </td>
    <td> <p>
   
	 48
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Projection
  </p> </td>
    <td> <p>
   
	 50
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 LCD
  </p> </td>
    <td> <p>
   
	 36
  </p> </td>
  </tr>
</table>


For more information about how to add attributes to components, see [Add an attribute to a component](add-an-attribute-to-a-component.md).

You can create system-defined and user-defined table constraints. For more information about these types of table constraints, see [About system-defined and user-defined table constraints](about-system-defined-and-user-defined-table-constraints.md).

## What syntax should be used to solve constraints in Microsoft Dynamics AX?

You must use Optimization Modeling Language (OML) syntax when you write the constraints. Microsoft Dynamics AX uses Microsoft Solver Foundation constraint solver to solve the constraints. For more information, see [Microsoft Solver Foundation](http://go.microsoft.com/fwlink/?linkid=217059).

## Should I use table constraints or expression constraints?

You can use either expression constraints or table constraints, depending on how you prefer to build the constraint setup. You build up a table constraint as a matrix, whereas an expression constraint is an individual statement. When you configure a product, it doesn't matter what kind of constraint is used. The following example illustrates the difference between the two methods.

When you configure a product by using the following constraint setup, the combinations that are allowed are a product in the color Black and in size 30 or 50, and a product in the color Red and in size 20.

**Table constraint setup**

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Color</p></th>
<th><p>Size</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Black</p></td>
<td><p>30</p></td>
</tr>
<tr class="even">
<td><p>Black</p></td>
<td><p>50</p></td>
</tr>
<tr class="odd">
<td><p>Red</p></td>
<td><p>20</p></td>
</tr>
</tbody>
</table>


**Expression constraint**

(Color == "Black" & (size == "30" | size == "50")) | (color == "Red" & size = "20")

## Should I use operators or infix notation when I write expression constraints?

You can write an expression constraint either by using the available prefix operators or by using infix notation. For the operators Min, Max, and Abs, you can't use an infix notation. These operators are included as a standard in most programming languages.

## What operators and infix notations can I use when I write expression constraints?

The following tables list the operators and infix notations that you can use when you write an expression constraint for a component in a product configuration model.

In the examples in this first table, you can see how to write an expression by using either infix notation or operators.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Operator</p></th>
<th><p>Description</p></th>
<th><p>Syntax</p></th>
<th><p>Examples</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Implies</p></td>
<td><p>This is true if the first condition is false, the second condition is true, or both.</p></td>
<td><p>Implies[a, b], infix: a -: b</p></td>
<td><p>Operator: Implies[x != 0, y &gt;= 0]</p>
<p>Infix notation: x != 0 -: y &gt;= 0</p></td>
</tr>
<tr class="even">
<td><p>And</p></td>
<td><p>This is true only if all conditions are true.</p>
<p>If the number of conditions is 0 (zero), it produces True.</p></td>
<td><p>And[args], infix: a &amp; b &amp; ... &amp; z</p></td>
<td><p>Operator: And[x == 2, y &lt;= 2]</p>
<p>Infix notation: x == 2 &amp; y &lt;= 2</p></td>
</tr>
<tr class="odd">
<td><p>Or</p></td>
<td><p>This is true if any condition is true.</p>
<p>If the number of conditions is 0 (zero), it produces False.</p></td>
<td><p>Or[args], infix: a | b | ... | z</p></td>
<td><p>Operator: Or[x == 2, y &lt;= 2]</p>
<p>Infix notation: x == 2 | y &lt;= 2</p></td>
</tr>
<tr class="even">
<td><p>Plus</p></td>
<td><p>This sums its conditions.</p>
<p>If the number of conditions is 0 (zero), it produces 0.</p></td>
<td><p>Plus[args], infix: a + b + ... + z</p></td>
<td><p>Operator: Plus[x, y, 2] == z</p>
<p>Infix notation: x + y + 2 == z</p></td>
</tr>
<tr class="odd">
<td><p>Minus</p></td>
<td><p>This negates its argument.</p>
<p>This must have exactly one condition.</p></td>
<td><p>Minus[expr], infix: -expr</p></td>
<td><p>Operator: Minus[x] == y</p>
<p>Infix notation: -x == y</p></td>
</tr>
<tr class="even">
<td><p>Abs</p></td>
<td><p>This takes the absolute value of its condition.</p>
<p>This must have exactly one condition.</p></td>
<td><p>Abs[expr]</p></td>
<td><p>Operator: Abs[x]</p></td>
</tr>
<tr class="odd">
<td><p>Times</p></td>
<td><p>This takes the product of its conditions.</p>
<p>If the number of conditions is 0 (zero), it produces 1.</p></td>
<td><p>Times[args], infix: a * b * ... * z</p></td>
<td><p>Operator: Times[x, y, 2] == z</p>
<p>Infix notation: x * y * 2 == z</p></td>
</tr>
<tr class="even">
<td><p>Power</p></td>
<td><p>This takes an exponential.</p>
<p>This applies exponentiation from right to left. That is, it is right-associative, and therefore Power[a, b, c] is equivalent to Power[a, Power[b, c]]. Power can only be used with a positive constant as the exponent.</p></td>
<td><p>Power[args], infix: a ^ b ^ ... ^ z</p></td>
<td><p>Operator: Power[x, 2] == y</p>
<p>Infix notation: x ^ 2 == y</p></td>
</tr>
<tr class="odd">
<td><p>Max</p></td>
<td><p>This produces the largest condition.</p>
<p>If the number of conditions is 0 (zero), it produces Infinity.</p></td>
<td><p>Max[args]</p></td>
<td><p>Operator: Max[x, y, 2] == z</p></td>
</tr>
<tr class="even">
<td><p>Min</p></td>
<td><p>This produces the smallest condition.</p>
<p>If the number of conditions is 0 (zero), it produces Infinity.</p></td>
<td><p>Min[args]</p></td>
<td><p>Operator: Min[x, y, 2] == z</p></td>
</tr>
<tr class="odd">
<td><p>Not</p></td>
<td><p>This produces the logical inverse of its condition.</p>
<p>This must have exactly one condition.</p></td>
<td><p>Not[expr], infix: !expr</p></td>
<td><p>Operator: Not[x] &amp; Not[y == 3]</p>
<p>Infix notation: !x!(y == 3)</p></td>
</tr>
</tbody>
</table>


The examples in the following table show how to write an infix notation.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Infix notation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>x + y + z</p></td>
<td><p>Addition</p></td>
</tr>
<tr class="even">
<td><p>x * y * z</p></td>
<td><p>Multiplication</p></td>
</tr>
<tr class="odd">
<td><p>x - y</p></td>
<td><p>Binary subtraction is translated the same as binary addition with a negated second.</p></td>
</tr>
<tr class="even">
<td><p>x ^ y ^ z</p></td>
<td><p>Exponentiation with right associativity</p></td>
</tr>
<tr class="odd">
<td><p>!x</p></td>
<td><p>Boolean not</p></td>
</tr>
<tr class="even">
<td><p>x -: y</p></td>
<td><p>Boolean implication</p></td>
</tr>
<tr class="odd">
<td><p>x | y | z</p></td>
<td><p>Boolean or</p></td>
</tr>
<tr class="even">
<td><p>x &amp; y &amp; z</p></td>
<td><p>Boolean and</p></td>
</tr>
<tr class="odd">
<td><p>x == y == z</p></td>
<td><p>Equality</p></td>
</tr>
<tr class="even">
<td><p>x != y != z</p></td>
<td><p>Distinct</p></td>
</tr>
<tr class="odd">
<td><p>x &lt; y &lt; z</p></td>
<td><p>Less than</p></td>
</tr>
<tr class="even">
<td><p>x &gt; y &gt; z</p></td>
<td><p>Greater than</p></td>
</tr>
<tr class="odd">
<td><p>x &lt;= y &lt;= z</p></td>
<td><p>Less than or equal to</p></td>
</tr>
<tr class="even">
<td><p>x &gt;= y &gt;= z</p></td>
<td><p>Greater than or equal to</p></td>
</tr>
<tr class="odd">
<td><p>(x)</p></td>
<td><p>Parentheses override default precedence.</p></td>
</tr>
</tbody>
</table>


## Why don't my expression constraints validate correctly?

You can't use reserved keywords as solver names for attributes, components, or subcomponents in a product configuration model. The following list contains the reserved keywords that you can't use:

  - Ceiling

  - Element

  - Equal

  - Floor

  - If

  - Less

  - Greater

  - Implies

  - Log

  - Max

  - Min

  - Minus

  - Plus

  - Power

  - Times

  - Slot

  - Model

  - Decision

  - Goal

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

