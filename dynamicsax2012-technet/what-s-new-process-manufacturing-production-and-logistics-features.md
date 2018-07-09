---
title: "What's new: Process manufacturing production and logistics features"
TOCTitle: Process manufacturing production and logistics features
ms:assetid: a2089acd-4b87-46c8-9e51-41bf16296fd4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527207(v=AX.60)
ms:contentKeyID: 59623336
ms.date: 11/14/2014
mtps_version: v=AX.60
---

# What's new: Process manufacturing production and logistics features [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012, Process manufacturing production and logistics has been enhanced with the addition of new features.

The features in Process manufacturing production and logistics help chemical manufacturers control and maximize assets; minimize operating costs; and monitor the impact of decisions on orders, production, inventory, and distribution. These features offer process and hybrid manufacturers solutions that address production and distribution. The features also provide manufacturers with integrated functionality for planning and managing production, distribution, procurement, and accounting.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Product areas affected</p></td>
<td><p>Process manufacturing production and logistics</p>
<p>Inventory management</p>
<p>Production control</p>
<p>Master planning</p>
<p>Product information management</p>
<p>Procurement and sourcing</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8

Support has been added for using recycled products in formulas. Recycled products must use the standard cost method. For more information, see [Set up recycled products in formulas](set-up-recycled-products-in-formulas.md).

## What’s new in Microsoft Dynamics AX 2012 R3

  - **Enhanced functionality for customer rebate agreements** – New options have been added to the customer rebate agreement form for item selection, cumulation, and line breaks. For more information, see [Create a customer rebate agreement](create-a-customer-rebate-agreement.md).

## Comparison with AX 2012 R2

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2012 R2</p></th>
<th><p>AX 2012 R3</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>When you create a customer rebate agreement, select multiple items that are not part of a predefined group.</p></td>
<td><p>To include multiple items in the rebate agreement, you must create an item group.</p></td>
<td><p>You can select multiple items from a tab in the rebate agreement form. You don't have to create an item group.</p></td>
<td><p>Provides a simple, flexible way to add multiple items to a rebate agreement.</p></td>
</tr>
<tr class="even">
<td><p>In the <strong>Cumulate sales by</strong> field, select the <strong>Lifetime</strong> option.</p></td>
<td><p>Not available</p></td>
<td><p>You can select the <strong>Lifetime</strong> option to cumulate sales over the validity period of the rebate agreement.</p></td>
<td><p>You have another option for the period over which sales are cumulated.</p></td>
</tr>
<tr class="odd">
<td><p>When you create rebate lines, use either sales amounts or sales quantities.</p></td>
<td><p>You can base rebate amounts only on the number of items that the customer purchases.</p></td>
<td><p>You can base rebate amounts either on the monetary value of the customer's purchase or on the number of items that the customer purchases.</p></td>
<td><p>You have more options for the criteria that you use on the rebate lines.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

  - **Potency management** – When you define an item, you can indicate that the item must have a specific concentration of an active ingredient. You can also adjust the quantity of material that is required in the production of the item, calculate the amount of money that is paid to a vendor for the item, and select an ingredient type for a formula line.

  - **Batch balancing for potency formulas** – You can add the actual value of a base inventory batch attribute to the registered inventory batch of a purchase order.

  - **Purchase pricing based on actual potency** – You can set up a pricing formula for potency items that is based on batch attributes. You can also define specific items that can be invoiced, based on the actual potency of the material that is received.

  - **Lot inheritance** – You can configure an item so that its batch attributes and shelf life information are updated based on the ingredients of the formula that is used to produce the item. You can use shelf life inheritance to define items. This means that the inventory batch with the earliest shelf life dates is updated or inherited by the product characteristics of the finished items. For batch attributes, you can define attributes for both the finished items and their ingredients, and select which ingredients pass along their characteristics or attribute values to the finished items. You can also select to have co-products updated with the same shelf life and batch attributes.

  - **Batch order sequencing** – You can use product sequencing to define one or more sequences that are assigned to various items. Product sequencing means you can sort production into a required order, so that changeover times are automatically reduced in production.

## Comparison with Microsoft Dynamics AX 2009

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012 R2</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create and post a purchase order for a potency item.</p></td>
<td><p>Not available.</p></td>
<td><p>You can define specific items that are invoiced based on the actual potency of the material that is received.</p></td>
<td><p>Items can be purchased by potency.</p></td>
</tr>
<tr class="even">
<td><p>Sequence planned batch orders.</p></td>
<td><p>Not available.</p></td>
<td><p>You can specify the order in which planned batch orders are produced and scheduled for resources that are bottlenecks.</p></td>
<td><p>You have more flexibility when you schedule planned batch orders.</p></td>
</tr>
<tr class="odd">
<td><p>Define formula ingredients for shelf life inheritance.</p></td>
<td><p>Not available.</p></td>
<td><p>You can define finished goods so that they are updated with information from the inventory batch. This information includes earliest shelf life dates and best-before dates.</p></td>
<td><p>You have the information that you require to manage the shelf life of perishable goods.</p></td>
</tr>
<tr class="even">
<td><p>Define and activate formula ingredients for batch attribute inheritance.</p></td>
<td><p>Not available.</p></td>
<td><p>You can select which product characteristics or attribute values are inherited by finished goods.</p></td>
<td><p>You can more easily define the characteristics of finished goods.</p></td>
</tr>
<tr class="odd">
<td><p>Define attribute-based pricing for a potency item.</p></td>
<td><p>Not available.</p></td>
<td><p>You can create a unique formula that defines how a purchase price is calculated for a potency item.</p></td>
<td><p>The calculation of prices for potency items is simplified.</p></td>
</tr>
<tr class="even">
<td><p>Use batch balancing.</p></td>
<td><p>Not available.</p></td>
<td><p>You can select the inventory batches of active ingredients based on the current potency. The inventory quantity that is required for the ingredients and batch order is calculated automatically.</p></td>
<td><p>Control over the potency of items that are selected for production is simplified.</p></td>
</tr>
</tbody>
</table>


## More information

For more information, see [Working with Process manufacturing production and logistics](working-with-process-manufacturing-production-and-logistics.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

