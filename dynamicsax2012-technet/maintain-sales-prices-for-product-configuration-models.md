---
title: Maintain sales prices for product configuration models
TOCTitle: Maintain sales prices for product configuration models
ms:assetid: 193b8926-123e-441c-a754-08bf319e1647
ms:mtpsurl: https://technet.microsoft.com/library/Dn527689(v=AX.60)
ms:contentKeyID: 59626222
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Maintain sales prices for product configuration models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To maintain sales prices for a product configuration model, you can set up a price model that is based on attributes. Attributes identify details that you want to maintain for products and attribute values that can affect the sales price of a product, such as sizes or dimensions.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Prerequisite</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>A product configuration model must be set up.</p></td>
<td><p>For more information about product configuration models, see <a href="about-product-configuration-models.md">About product configuration models</a>.</p></td>
</tr>
<tr class="even">
<td><p>Products that you want to configure using a configuration model must be associated with the configuration model.</p></td>
<td><p>Products are associated with a product configuration model using a specific version of the product configuration model. For more information, see <a href="setting-up-and-maintaining-product-configuration-models.md">Setting up and maintaining product configuration models</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Attribute-based pricing must be active.</p></td>
<td><p>Attribute-based pricing is enabled for a product configuration model using a specific version of the product configuration model. For more information, see “Set attribute-based pricing for a version of a product configuration model” in the following sections.</p></td>
</tr>
<tr class="even">
<td><p>Price model criteria must be set up for a price model.</p></td>
<td><p>Define search criteria for the price model to limit the search for sales orders, sales quotations, or quotation prospects that can match the price model. For more information, see “Define price model criteria” in the following sections.</p></td>
</tr>
<tr class="odd">
<td><p>A default currency must be set.</p></td>
<td><p>To use price models, you must provide a currency for the price models.</p>
<ul>
<li><p>Click <strong>Project management and accounting</strong> &gt; <strong>Setup</strong> &gt; <strong>Project management and accounting parameters</strong>. Click the <strong>Constraint-Based product configuration models</strong> link and then select a currency in the <strong>Default currency</strong> field.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Optionally, attach a price breakdown document to your orders.</p></td>
<td><p>To attach a breakdown of component prices to all sales orders, sales quotations, and quotation prospects, the <strong>Price breakdown</strong> parameter must be enabled. For more information, see “Attach a price breakdown document to an order” in the following sections.</p></td>
</tr>
</tbody>
</table>


## Define a price model for a product configuration model

A price model can include a base price and a set of expressions that modify the total unit price of the configurable product. You can set up a base price for the root component of the product model and for the subcomponents. The total sales price of the model is derived from the total sum of the price that is set up for the components.

To define a price model for a product configuration model, follow these steps:

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select a product configuration model. On the **Action Pane**, in the **Set up** group, select **Price models**.

3.  In the **Price models** form, click **New**, and then enter a name and a description for the price model.

4.  Click **Edit** to open the **Price model** form.

5.  Select a component and then click **Base price expression** to add a base price for the component.

6.  Optionally, under **Expression rules**, click **Add** to add expression rules that will modify the base price for each component.

7.  Repeat step 5, and optionally repeat step 6, for each component that you want to set a price for.

## Set attribute-based pricing for a version of a product configuration model

You can set attribute-based pricing for a version of a product configuration model. This enables you to specify that products using the model are priced according to an attribute-based price model.

To set attribute-based pricing for a version of a product configuration model, follow these steps:

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select a product configuration model. On the **Action Pane**, in the **Product model details** group, select **Versions**.

3.  Click **New** and, in the **Product number** field, select the product that you want to associate with the product configuration model.

4.  In the **Pricing method** field, select **Attribute based**.

## View the price breakdown of a product configuration model

When you configure a product, you can see how each price expression in a product configuration model adds to the total price of the product. You can also adjust the attribute values of the model. You can then open a price breakdown to view the current sales price for each component of a configurable product.

To view the price breakdown of a product configuration model, follow these steps:

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select a product configuration model. On the **Action Pane**, in the **Set up** group, select **Price models**.

3.  In the **Price models** form, select a price model, and then click **Edit**.

4.  In the **Price model** form, click **Test** to open the **Configure line** form and select attribute values.
    
    Optionally, click **Load template** to select a template with a set of saved attribute values. If needed, you can change the attribute values when you configure the model. Click **OK** to close the form and continue with the configuration in the **Configure line** form.

5.  Click **Next** to continue with the configuration and set up or adjust attribute values.

6.  When you configure the attribute pages, you can click **View price breakdown** to open an Excel spreadsheet with an overview of the sales price breakdown. The pages in the **Configure line** form are for each component of the product configuration model. Regardless of what page is active when you click **View price breakdown**, the price breakdown will always show all active price elements for the configuration. If you change any of the price elements when you configure the model, you must open a new instance of the price breakdown to get the current prices.

## View the price breakdown when you configure a product on a sales order line

When you configure a product on a sales order line, a sales quotation line, or a quotation prospect line you see how the components of the product configuration model add to the total price of the product.

To view the price breakdown when you configure a product on a sales order line, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **Action Pane** in the **New** group, click **Sales order** to create a new sales order.

3.  Create a sales order line, click **Product and supply**, and then select **Configure line**.

4.  Follow steps 5 and 6 in “View the price breakdown of a product configuration model” to complete the configuration and to open an Excel spreadsheet with a price breakdown.

## Attach a price breakdown document to an order

You can attach the price breakdown of a product as a document to a sales order, sales quotation, or quotation prospect.

To enable attachment of a price breakdown document, follow these steps:

1.  Click **Product information management** \> **Setup** \> **Product information management parameters**.

2.  Click the **Constraint-Based product configuration models** link and select **Price breakdown**. When the **Price breakdown** parameter is enabled, the sales price breakdown is automatically attached as a document to the orders that you create.

To view the sales breakdown document on a sales order, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order. In the **Sales order** form, click the **Document handling** icon on the status bar to open the **Document handling** form and view the attached price breakdown document.

## Save a price model setup as a configuration template

You can save the attribute values for a configuration model as a template. The template can include a set of saved attribute values that you can change when you configure the model.

To save a price model setup as a configuration template, follow these steps:

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select a product configuration model. On the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  On the **Action Pane**, in the **Product model details** group, click **Configuration templates**.

4.  Click **New** to create a new template, enter a name, and then click **Modify**.

5.  In the **Configure line** form, click **Next** to step through the setup of each component and enter or adjust attribute values.

6.  Click **OK** to close the **Product configuration template** form. In the **Configuration templates** form, select **Active** to enable the template.

## Define price model criteria

Price model criteria are search criteria that match a sales order or sales quotation with a specific price model. The search criteria can have an optional detail level. In each legal entity, if you plan to use a price model you must set up at least one price model criteria for the price model. This is how the price model is associated with your orders.

To define price model criteria, follow these steps:

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select a product configuration model. On the **Action Pane**, in the **Set up** group, select **Price model criteria**.

3.  In the **Price model criteria** form, click **New**, and enter the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter a name for the price model criteria.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Description</strong></p></td>
    <td><p>Enter a description for the price model criteria.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Price model</strong></p></td>
    <td><p>Select the price model that you want to associate with the criteria.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Order type</strong></p></td>
    <td><p>Select from the following options:</p>
    <ul>
    <li><p><strong>Quotation type customer</strong> – The criteria is for a quotation account of the type <strong>Customer</strong>.</p></li>
    <li><p><strong>Quotation type prospect</strong> – The criteria is for a quotation account of the type <strong>Prospect</strong>.</p></li>
    <li><p><strong>Sales order</strong> – The criteria is for a sales order.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Valid from</strong></p></td>
    <td><p>The date from which the criteria is valid.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Expire by</strong></p></td>
    <td><p>The date when the criteria expires. If you leave the field blank, the criteria has no expiration date.</p></td>
    </tr>
    </tbody>
    </table>


4.  Click **Edit** to open a query. You can use the query to specify detailed search criteria for the price model, such as specific sales orders or line numbers.

5.  Click **Add** or **Remove** to add or remove criteria, and then click **OK** to close the form.

  


