---
title: About system-defined and user-defined table constraints
TOCTitle: About system-defined and user-defined table constraints
ms:assetid: c0cca2bf-bb1d-4468-b2a0-cf5b8303e188
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597232(v=AX.60)
ms:contentKeyID: 39519305
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product configurator
- table constraint
- user-defined
---

# About system-defined and user-defined table constraints 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can declare two types of constraints in a product configuration model.

  - Expression constraint – Use to express relations between attributes to make sure that only compatible values can be selected during product configuration. For more information, see [Create an expression constraint for a product component](create-an-expression-constraint-for-a-product-component.md).

  - Table constraint – Create a table that defines all of the combinations that are allowed for a specified set of attributes. Two types of table constraints are available: user-defined table constraints and system-defined table constraints.

This topic describes table constraints that are user-defined and system-defined for components in a product configuration model.

## User-defined table constraints

A user-defined table constraint is a type of matrix that is used to describe the combinations for the attribute values that are defined by attribute types.

For example, if you produce televisions, you could include columns for the TV size and TV type in the user-defined table constraint. Plasma televisions are only available in 42 and 50 inch screen sizes. Projection televisions are available only in 50 or 60 inch screen sizes. The following table shows the information that is displayed on the **Allowed combinations** tab in the **Edit table constraint** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>TV type</p></th>
<th><p>TV size</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Plasma</p></td>
<td><p>42</p></td>
</tr>
<tr class="even">
<td><p>Plasma</p></td>
<td><p>50</p></td>
</tr>
<tr class="odd">
<td><p>Projection</p></td>
<td><p>50</p></td>
</tr>
<tr class="even">
<td><p>Projection</p></td>
<td><p>60</p></td>
</tr>
</tbody>
</table>


User-defined table constraints are defined by static table input that functions the same way as an expression constraint. When you use a user-defined table constraint, the advantage is that tables are often easier to create, understand, and maintain than long expression constraints.

## System-defined table constraints

A system-defined table constraint creates a dynamic mapping between an attribute in a product configuration model and a field in a Microsoft Dynamics AX 2012 table. The product configuration model uses the mapping and then reflects the data in the Microsoft Dynamics AX 2012 table. System-defined table constraints bind columns of a table to attributes for components in a product model. The result is a dynamic constraint, because the table can be modified, for example, by other Microsoft Dynamics AX 2012 modules or maintained by partners.

When you create a system-defined table constraint, you select a table, define the query to use, and then associate attribute types to the fields on the selected table. The types of fields must match the types of attribute types. However, it is not required to match such values as enumeration values and integer ranges. The attribute type values are replaced by the values in the field from the selected table. After you create this type of table constraint, you can add the constraint to a component, and then map the attribute to the column names in the table constraint.

## See also

[Create a table constraint](create-a-table-constraint.md)

[Add a table constraint to a component](add-a-table-constraint-to-a-component.md)

[About reusing configurations](about-reusing-configurations.md)

[About product configuration models](about-product-configuration-models.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

