---
title: Set up recycled products in formulas
TOCTitle: Set up recycled products in formulas
ms:assetid: 6f96ebde-62bd-4151-bdbf-1df86c174f8e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn762134(v=AX.60)
ms:contentKeyID: 63378891
ms.date: 11/13/2014
mtps_version: v=AX.60
---

# Set up recycled products in formulas [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up recycled products in formulas when using process industries production. Recycling a produced output product, so that it can be reused as an input product in the same production process, is a common industry scenario. For example, a stamping process in a foundry may produce metal scrap as a by-product. This metal scrap may then be consumed subsequently as an ingredient in the same process. Working with recycled products in formulas requires setup of the products that will be recycled, and the formulas that will consume and produce recycled products.


> [!NOTE]
> <P>After the setup is complete, the supply of recycled products from planned and firmed batch orders is not included in master planning. This prevents the supply from being pegged against the demand for the recycled product from the same order, process, or BOM chain. The recycled product becomes available as on-hand inventory only when the batch order has been posted.</P>



## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<td><p>Setup</p></td>
<td><p>Standard costs have been set up. For more information, see <a href="setting-up-and-maintaining-standard-costs.md">Setting up and maintaining standard costs</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up a product to use standard cost

Recycled products must use the standard cost method. The joint production costs that are allocated to the formula and co-products are deducted by using the standard cost value of the recycled by-product.

Define standard cost on the item model group that the item is assigned to. The item model group determines how to calculate the consumption of the item. To assign standard cost, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click the product to open the **Released product details** form.

3.  On the **General** FastTab, in the **Administration** field group, in the **Item model group** field, select an item model group that has been set up for standard cost.

## 2\. Define a product as a formula by-product

When you define a product as a formula by-product, it can be recycled for consumption.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click the product to open the **Released product details** form.

3.  On the **Engineer** FastTab, in the **Formula planning** field group, in the **Production type** field, select **By-product**.

## 3\. Set up a formula that consumes a recycled product

This task adds the recycled product as an input ingredient in a formula.

1.  Create a formula and formula version. For more information, see [Create a formula and formula version](create-a-formula-and-formula-version.md).

2.  In the **Formula** form, select the formula, and then click **Lines** to add an ingredient to the formula.

3.  In the **Formula line** form, create a line that specifies the by-product as an input ingredient to the formula.

## 4\. Set up a formula that produces a recycled product

This task defines the recycled product as an output by-product of a formula.

1.  In the **Formula** form, select the version and then click **Co-products**.

2.  In the **Co-products** form, add a line for the by-product. The **Production type** must be **By-product**.
    

    > [!TIP]
    > <P>You can also use products that have the production type <STRONG>Co-product</STRONG>, but then you must change this to <STRONG>By-product</STRONG> on the formula or batch order.</P>



3.  In the **Burden** field, select **Recycled**. The burden type determines how to handle the cost of the recycled by-product.

## Related tasks

[Create a formula and formula version](create-a-formula-and-formula-version.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>, and then select the <strong>Process manufacturing</strong> license key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Production planner</p></td>
</tr>
</tbody>
</table>


## See also

[Setting up and maintaining standard costs](setting-up-and-maintaining-standard-costs.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

