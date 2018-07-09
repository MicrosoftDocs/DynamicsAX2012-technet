---
title: "What's new: Product information management features"
TOCTitle: Product information management features
ms:assetid: 44620561-2b42-4a4d-99f6-c952b74de93d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507124(v=AX.60)
ms:contentKeyID: 59623213
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Product information management features [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Product information management](product-information-management.md) area for Microsoft Dynamics AX 2012. To learn more, refer to the tables that apply to your version of the product.

## What’s new in Microsoft Dynamics AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Product configuration Application Programming Interface</p></td>
<td><p>An Application programming interface (API) is available to help existing customers who are using Product builder to migrate their existing product builder models to new product configuration models. The API will also provide a tool for developers to extend new product configuration model functionality.</p>
<p>For more information, see the white paper titled <a href="http://blogs.msdn.com/cfs-filesystemfile.ashx/__key/communityserver-components-postattachments/00-10-36-90-26/migrate-from-product-builder-to-product-configurator-microsoft-dynamics-ax-2012.pdf">Migrate from Product builder to Product configurator</a>.</p></td>
</tr>
<tr class="even">
<td><p>Product configurator</p></td>
<td><p><strong>New Product configuration functionality</strong></p>
<p>The Product configurator is a constraint-based product configuration tool that leverages the Microsoft Solver Foundation product. You can use the Product configurator to create and maintain product models, and to reuse product models, components, and attributes. You also can use the Product configurator to configure items on a sales order and use configuration templates to preset frequently used configuration selections.</p>
<p>For more information, see the topic titled <a href="setting-up-and-maintaining-product-configurations.md">Setting up and maintaining product configurations</a>.</p>
<p><strong>Product configurator and Enterprise Portal</strong></p>
<p>You can access Product configurator through Enterprise Portal, and you can configure constraint-based product configuration models, as well as modify existing configurations through Enterprise Portal.</p>
<p>For more information, see the topic titled <a href="create-or-edit-a-sales-order.md">Create or edit a sales order</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The <strong>Configuration</strong> form in Product configurator is easier to extend</p></td>
<td><p>To improve the extendibility of the <strong>Configure line</strong> form that is used during a configuration session in Product configurator, a new form that is based on X++ is now available as the default configuration form. Businesses can now select whether they want to use a configuration form that is based on the Windows Presentation Foundation, or one that is based on X++.</p>
<p>For more information about customizing Microsoft Dynamics AX forms, see the topic titled <a href="https://technet.microsoft.com/en-us/library/aa881211(v=ax.60)">Forms in Microsoft Dynamics AX</a>.</p></td>
</tr>
<tr class="even">
<td><p>Improvements to planning tools</p>
<p></p></td>
<td><p>You can now view the relationships between actions on planned orders. You can also view relationships to orders that are already approved. This makes it easier to prioritize orders, and to focus on auto firming derived requirements.</p>
<p>For more information, see the topic titled <a href="about-using-tracing-for-master-plans.md">About using tracing for master plans</a>.</p>
<p>Features are introduced for setting parameters for planning to make it easier to understand how parameter settings can affect data in Microsoft Dynamics AX. When you run explosion, you can now turn on a log to record how master planning requirements are generated for a specific order. This makes it easier to identify why an order was generated in a certain way. You can run master planning again in a simulation plan, so that neither the dynamic plan nor the static plan is affected.</p>
<p>For more information, see the topics titled <a href="about-master-scheduling-plans.md">About master scheduling plans</a> and <a href="set-up-tracing-for-master-plans.md">Set up tracing for master plans</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Improvements made to the overview of production information, approval and calculation of worker registration on projection jobs, and worker absences</p>
<p></p></td>
<td><p>Fields and controls have been added to the <strong>Edit job list</strong> form to provide shop floor supervisors with a better overview of the production information involved in production orders. The additions include an improved ability to prioritize jobs, change the resource that is assigned to a selected job, add attachments, and view information about the materials and route directly from the <strong>Edit job list</strong> form.</p>
<p>For more information, see the topic titled <a href="https://technet.microsoft.com/en-us/library/hh209583(v=ax.60)">Edit job list (form)</a>.</p>
<p>Improvements have also been made to the features for approving and calculating worker registrations on production jobs and absence. A new <strong>Week</strong> view has been added to enable an approver to view and manage registrations for an individual worker for a full work week.</p>
<p>For more information, see the topic titled <a href="about-calculating-approving-and-transferring-registrations.md">About calculating, approving and transferring registrations</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhanced modeling capabilities in Product configurator</p>
<p></p></td>
<td><p>You can set up a product configuration model so that the system will automatically reuse a configuration when a user makes selections that match the criteria for its reuse. Setting the criteria that determine whether the system will reuse a configuration starts with specifying that the component is reusable, and then selecting the attributes that a user's selections must match during a configuration session. When a user completes a configuration session, the system searches for a matching configuration. If the system locates a configuration that meets these criteria, it reuses the configuration ID and the associated BOM and route. For more information, see the topic titled <a href="about-reusing-configurations.md">About reusing configurations</a>.</p>
<p>You can now specify that an attribute is read-only when a user is configuring a product. This new attribute modifier has been placed together with the hide and mandatory modifiers on the Attributes FastTab. For more information, see the topic titled <a href="add-an-attribute-to-a-component.md">Add an attribute to a component</a>.</p>
<p>When mapping the fields in a table constraint to the attributes of a component, in addition to using attributes on the component itself, a user can now also use attributes from subcomponents of the component. For more information, see the topic titled <a href="about-system-defined-and-user-defined-table-constraints.md">About system-defined and user-defined table constraints</a>.</p>
<p>Default attribute values are now considered to be of the same class as attribute values selected by a configuration user. Thus, having one or more default values in contradiction with each other or with a constraint will give an error when a configuration is tested or executed. The consequence of this is that it might be necessary to revise the default attribute values for product configuration models. For more information, see <a href="about-product-configuration-models.md">About product configuration models</a>.</p>
<p></p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expression editor enhancements</p></td>
<td><p>The expression editor has been updated to comply with the industry standard that a product designer expects for building expressions in Microsoft Dynamics AX. The main enhancements include the following features:</p>
<ul>
<li><p>The user interface has been updated to enable you to easily build expressions using operators, attributes, and attribute values.</p></li>
<li><p>A feedback mechanism has been created to enable you to easily identify errors when you validate the expressions that you write.</p></li>
</ul>
<p>For more information, see <a href="create-an-expression-constraint-for-a-product-component.md">Create an expression constraint for a product component</a> and <a href="expression-constraints-and-table-constraints.md">Expression constraints and table constraints</a>.</p></td>
</tr>
<tr class="even">
<td><p>Calculations in product configuration models</p></td>
<td><p>When you work with product configuration models, you can now use calculations to test the impact of different decimal numbers when you configure a product.</p>
<p>Calculations are new concepts that complement constraints, and they include a larger set of operators than the operators that are available for constraints. A calculation consists of a target attribute and a calculation expression. The target attribute receives the result of the calculation.</p>
<p>In the following example, the target attribute has a Boolean type and the calculation uses an If expression:</p>
<p>If[(decimalAttribute1 / decimalAttribute2) &lt; 1, True, False]</p>
<p>The expression returns the value “True” to the target attribute if decimalAttribute2 is greater than or equal to decimalAttribute1, and “False” if it is not.</p>
<p>For more information, see <a href="create-calculations.md">Create calculations</a> and <a href="calculations-for-product-configuration-models.md">Calculations for product configuration models</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Determine prices using a product configuration model</p></td>
<td><p>You can now define individual prices for product options using a configuration model. Each component in a product configuration model has a base price. You can use expression rules to associate attributes with a value that affects the total price. When you configure a product and select a product option for the component, you can see how the option contributes to the total price of the product configuration model.</p>
<p>For more information, see <a href="maintain-sales-prices-for-product-configuration-models.md">Maintain sales prices for product configuration models</a>.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

