---
title: Setting up and maintaining product configuration models
TOCTitle: Setting up and maintaining product configuration models
ms:assetid: c5971350-4212-4193-a91f-883a735d97f9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh278335(v=AX.60)
ms:contentKeyID: 36207232
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product configurator
- constraint-based
- setting up product configuration models
---

# Setting up and maintaining product configuration models [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains information about setting up and maintaining product configuration models.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a product master</p></td>
<td><p>Create a product master in the <strong>Released product details</strong> form. A product master which is used in a product configuration model or as a subcomponent must have <strong>Constraint-based configuration</strong> selected for the <strong>Configuration technology</strong> and the configuration dimension selected for the product dimension group. For more information, see <a href="key-tasks-define-products.md">Key tasks: Define products</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create components</p></td>
<td><p>Create components in the <strong>Components</strong> form. Components are the building blocks of a product configuration model and can be reused in multiple product configuration models. For more information, see <a href="create-components.md">Create components</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create attribute types</p></td>
<td><p>Create attribute types in the <strong>Attribute types</strong> form. Attribute types are defined to specify the set of data types for all attributes that are used in product configuration models. Booleans, texts with fixed lists and integers with ranges, list the set of values are available when you configure a product configuration model. <a href="create-attribute-types.md">Create attribute types</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create a product configuration model</p></td>
<td><p>Create a product configuration model in the <strong>New product configuration model</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p>Create attributes</p></td>
<td><p>Create an attribute in the <strong>Constraint-based product configuration model details</strong> form on the <strong>Attributes</strong> FastTab. Attributes describe the features of the product configuration model.</p></td>
</tr>
<tr class="even">
<td><p>Create constraints</p></td>
<td><p>Create constraints in the <strong>Constraint-based product configuration model details</strong> form on the <strong>Constraints</strong> FastTab. Constraints are conditions that the product configuration model must satisfy. Constraints are either expression constraints or table constraints. For more information, see <a href="about-system-defined-and-user-defined-table-constraints.md">About system-defined and user-defined table constraints</a> and <a href="create-an-expression-constraint-for-a-product-component.md">Create an expression constraint for a product component</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create subcomponents</p></td>
<td><p>Create subcomponents in the <strong>Constraint-based product configuration model details</strong> form on the <strong>Subcomponents</strong> FastTab. Subcomponents are related to components and they are linked to items that represent the subcomponent. For more information, see <a href="create-a-subcomponent-for-a-component.md">Create a subcomponent for a component</a>.</p></td>
</tr>
<tr class="even">
<td><p>Add user requirements to a product configuration model</p></td>
<td><p>User requirements are used to represent preselected options for a product configuration model. For example, the person who took the sales order can ask the customer where the home theater system is to be installed. The room size could be a configuration requirement that is used to select a value for a specific component.</p></td>
</tr>
<tr class="odd">
<td><p>Add BOM lines to a product configuration model</p></td>
<td><p>Create BOM lines in the <strong>Constraint-based product configuration model details</strong> form on the <strong>BOM lines</strong> FastTab. BOM lines represent a part required to build the product. For more information, see <a href="add-a-bom-line-to-a-component.md">Add a BOM line to a component</a>.</p></td>
</tr>
<tr class="even">
<td><p>Add route operations to a product configuration model</p></td>
<td><p>Create route operations in the <strong>Constraint-based product configuration model details</strong> form on the <strong>Route operations</strong> FastTab. Route operations represent a step in a sequence of steps performed to make the product. For more information, see <a href="add-a-route-operation-to-a-component.md">Add a route operation to a component</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create an active version for a product configuration model</p></td>
<td><p>Create an active version of the product configuration model in the <strong>Versions</strong> form. A version is the relationship between a product configuration model and a product master. A product configuration model that has an active version can be configured from a sales order, sales quotation, purchase order or production order. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh208624(v=ax.60)">Versions (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Test a product configuration model</p></td>
<td><p>Test the product configuration model from either the <strong>Constraint-based product configuration model details</strong> form or from the <strong>Product configuration models</strong> list page. Testing the product configuration models simulates the product model configuration process that occurs during the order handling. For more information, see <a href="test-a-product-configuration-model.md">Test a product configuration model</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create product configuration model template</p></td>
<td><p>Create a product configuration model template in the <strong>Configuration templates</strong> form. A configuration template includes values for attributes in the product configuration model. Select the attribute values in the <strong>Configure line</strong> form. You can select to load a product model configuration template during the product model configuration process. For more information, see <a href="create-a-product-configuration-template.md">Create a product configuration template</a>.</p></td>
</tr>
<tr class="even">
<td><p>Configure an item</p></td>
<td><p>Product configuration models can be configured from a sales order, sales quotation, purchase order or a production order.</p></td>
</tr>
</tbody>
</table>


## See also

[About product configuration models](about-product-configuration-models.md)

[About reusing configurations](about-reusing-configurations.md)

[Constraint-based product configuration model details (form)](https://technet.microsoft.com/en-us/library/hh209626\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

