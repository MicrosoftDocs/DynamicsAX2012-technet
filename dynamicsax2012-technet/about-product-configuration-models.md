---
title: About product configuration models
TOCTitle: About product configuration models
ms:assetid: 5ccae80d-77cb-4c14-be69-5744390903dd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh278332(v=AX.60)
ms:contentKeyID: 36207230
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About product configuration models [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Product configuration models are created to represent a generic product structure. When you set up a product configuration model, you can create a distinct product variant that has a unique bill of materials (BOM) and a unique route. Product configuration models are based on constraints and use Microsoft Solver Foundation. You can configure items on sales orders, sales quotations, purchase orders, and production orders.

The following table describes the table constraint-based terms and concepts.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Microsoft Solver Foundation</p></td>
<td><p>Product configurator uses Solver Foundation to solve expression constraints and conditions. Solver Foundation is used to find one or more valid solutions, and to eliminate values that are not valid for product configuration models. For more information, see <a href="http://go.microsoft.com/fwlink/?linkid=217059">Microsoft Solver Foundation</a> on the MSDN website.</p></td>
</tr>
<tr class="even">
<td><p>Components</p></td>
<td><p>Components are the main building blocks of a product configuration model. Components are displayed in a tree structure in the <strong>Constraint-based product configuration model details</strong> form. Components can contain the following elements:</p>
<ul>
<li><p>Attributes</p></li>
<li><p>Constraints</p></li>
<li><p>Subcomponents</p></li>
<li><p>User requirements</p></li>
<li><p>BOM lines</p></li>
<li><p>Route operations</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Attributes</p></td>
<td><p>Attributes describe all the features of the product configuration model. You can use attributes to specify the features that can be selected when a distinct product is configured. Attributes are used in constraints and conditions. When attributes are created and added to a product configuration model, the related attribute types are referenced.</p>
<p>A default value can be set for an attribute. The default value is used in the configuration user interface (UI) when the product configuration model is configured.</p>
<p>You can specify that an attribute is mandatory, read-only, or hidden.</p>
<ul>
<li><p>Mandatory – A value must be set for the attribute when the product is configured.</p></li>
<li><p>Read-only – The attribute value is displayed during a configuration session, but it cannot be changed.</p></li>
<li><p>Hidden – The attribute value is included in constraints and conditions, but is not displayed during a configuration session.</p></li>
</ul>
<p>You can also specify a condition for attributes. If the condition is met, a value must be entered for the mandatory attribute. Conditions are expressions that must be met for attributes, BOM lines, and route operations to be included in a product configuration model. Any attribute that is referenced in a condition becomes mandatory. We recommend that you select the attribute as mandatory on the <strong>Attributes</strong> tab. This can make it easier to identify mandatory attributes.</p>
<p>Attribute values are an important part of reusing configurations. The system uses attribute values to determine whether a configuration exists that matches the selections that a user made during a configuration session. For more information, see <a href="about-reusing-configurations.md">About reusing configurations</a>.</p></td>
</tr>
<tr class="even">
<td><p>Attribute types</p></td>
<td><p>Attribute types specify the set of data types for attributes that are used in a product configuration model.</p>
<p>The following attribute types are used:</p>
<ul>
<li><p><strong>Integer</strong> – Integers that have a range.</p></li>
<li><p><strong>Decimal</strong></p></li>
<li><p><strong>Text</strong> – Texts that have a fixed list.</p></li>
<li><p><strong>Boolean</strong></p></li>
</ul>
<p>If the attribute type is <strong>Boolean</strong>, <strong>Integer</strong>, or <strong>Text</strong>, the set of values is available when a product configuration model is set up.</p>
<div class="alert">

> [!NOTE]
> <P>Solver Foundation recognizes only the following attribute types: Booleans, texts that have a fixed list, and integers that have a range. Therefore, only these attribute types can be used in expression constraints and conditions.</P>
> <P>You can also use the <STRONG>Attribute types</STRONG> form to define attribute types for products and catalogs.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Constraints</p></td>
<td><p>Constraints describe the restrictions of the product model configuration. Constraints are used to guarantee that only valid values are selected when the product configuration model is set up.</p>
<p>Constraints can be either expression constraints or table constraints:</p>
<ul>
<li><p>Expression constraints can be used only for the component that they are tied to. The expression constraints for a component can reference attributes of the component's subcomponents. Solver Foundation is used to solve the constraints, and you must use the syntax of Solver Foundation when you write the constraints. For more information, see <a href="http://go.microsoft.com/fwlink/?linkid=217059">Microsoft Solver Foundation</a>.</p></li>
<li><p>Table constraints can be either user defined or system defined.</p>
<p>A user-defined table constraint is a type of matrix that can be used to describe the set of combinations for the attribute values that are defined by attribute types. For example, if televisions are produced, the matrix for the user-defined table constraint might have columns for the television size and type.</p></li>
</ul>
<p><strong>Example</strong></p>
<p>Televisions of the Plasma type are available only in sizes 42 or 50. Televisions of the Projection type are available only in sizes 50 or 60. The following table shows the information that is displayed on the <strong>Allowed combinations</strong> tab in the <strong>Edit table constraint</strong> form.</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Television type</p></th>
<th><p>Television size</p></th>
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

</div>
<p>A system-defined table constraint represents a mapping between an attribute and a field in a Microsoft Dynamics AX table. A system-defined table constraint dynamically links the attribute to the field. By using the link, the product configuration model reflects the data in the Microsoft Dynamics AX table.</p></td>
</tr>
<tr class="even">
<td><p>Subcomponents</p></td>
<td><p>Subcomponents reflect the tree structure of the product configuration model. You can use subcomponents to build the structure of the product configuration model. Subcomponents reference existing components. Therefore, using subcomponents encourages the reuse of components in multiple product configuration models. In the <strong>BOM line details</strong> form for a subcomponent, you can select a distinct value for the subcomponent. Alternatively, you can select an attribute for which the value is selected when the product configuration model is set up.</p>
<p>To include a product as a component or subcomponent, you must specify the following in the <strong>Create product</strong> form when you create the product:</p>
<ul>
<li><p>In the <strong>Product type</strong> field, select <strong>Item</strong>.</p></li>
<li><p>In the <strong>Product subtype</strong> field, select <strong>Product master</strong>.</p></li>
<li><p>In the <strong>Configuration technology</strong> field, select <strong>Constraint-based configuration</strong>.</p></li>
</ul>
<p>You can view whether a released product can be used as a component or subcomponent on the <strong>General</strong> tab of the <strong>Released product details</strong> form. If <strong>Constraint-based configuration</strong> is selected in the <strong>Configuration technology</strong> field, the product can be used as a component or subcomponent.</p>
<p>You can hide subcomponents so that they are not displayed to the user during a configuration session. Attributes, subcomponents, and user requirements that are related to the subcomponent are also hidden.</p></td>
</tr>
<tr class="odd">
<td><p>User requirements</p></td>
<td><p>User requirements represent an abstraction between user requirements and specific components and attributes. You cannot map a user requirement to an item. For example, a customer is shopping for a home theater system. The sales representative might ask about the size of the room where the customer plans to install the system, to determine how many watts are required. In this example, the room size can be a user requirement that helps determine the appropriate attribute value for a specific component.</p>
<p>You can hide user requirements so that they are not displayed to the user during a configuration session. Attributes, subcomponents, and user requirements that are related to the user requirement are also hidden. You can write a condition to control whether a user requirement can be hidden. You must write the condition using Optimization Modeling Language (OML) syntax.</p></td>
</tr>
<tr class="even">
<td><p>BOM lines</p></td>
<td><p>BOM lines represent the individual materials of the components in the product configuration model. In the <strong>BOM line details</strong> form, all items are available for selection. A condition can be added to the BOM line so that the BOM lines that are selected for a distinct product variant can vary, based on the user's selection when the product configuration model is set up. Conditions are expressions that must be met for attributes, BOM lines, and route operations to be included in a product configuration model. In the <strong>BOM line details</strong> form, you can select a distinct value. Alternatively, you can map to an attribute for which the value is selected when the product configuration model is set up.</p></td>
</tr>
<tr class="odd">
<td><p>Route operations</p></td>
<td><p>In the <strong>Route operation details</strong> form, you can select a distinct value. Alternatively, you can map to an attribute for which the value is selected when the product configuration model is set up. Conditions are written like expression constraints. Conditions are expressions that must be met for attributes, BOM lines, and route operations to be included in a product configuration model.</p></td>
</tr>
</tbody>
</table>


## See also

[Constraint-based product configuration model details (form)](https://technet.microsoft.com/en-us/library/hh209626\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

