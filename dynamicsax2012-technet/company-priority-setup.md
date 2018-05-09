---
title: Company priority setup
TOCTitle: Company priority setup
ms:assetid: fa580295-4ca8-44d7-a9e0-a0eae4a9d83b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg723957(v=AX.60)
ms:contentKeyID: 35133311
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Company priority setup 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you merge the data from more than one company, the priority of the companies determines which company's values take priority for the data.

Use the **Company priority setup** form to define the priority of companies.


> [!NOTE]
> <P>You must set up the company priority only if you upgrade items from more than one company.</P>



## Company priority affects product numbers and item dimension values

The company priority affects the following data when items are mapped to products:

  - The sequence of product numbers

  - The names and descriptions for sizes, colors, and configurations

## Company priority and the sequence of product numbers

If the items that you map to a product have identical numbers but come from different companies, the sequence of product numbers is determined by the company priority. For more information, see the description of the 1:1 mapping method in [Product upgrade (preprocessing)](product-upgrade-preprocessing.md).

## Company priority and the names and descriptions of item dimensions

If the items that you map to a product have identical item numbers but come from different companies, the active item dimensions of these items may have different names and descriptions. When several items are mapped to one product, the names and descriptions of the item dimensions are consolidated. The names and descriptions from the company that has the highest priority are used.

**Example**

  - Three identical items are mapped to one product. The items come from three different companies, C1, C2, and C3.

  - The priority of C1 is 1, the priority of C2 is 2, and the priority of C3 is 3.

  - The item has one active dimension, Color. However, the name of the dimension is not the same in the three companies.

The following table shows this setup.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Company</p></th>
<th><p>Item</p></th>
<th><p>Item dimension</p></th>
<th><p>Item dimension name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>C1</p></td>
<td><p>INV-1000</p></td>
<td><p>Color</p></td>
<td><p>Red</p></td>
</tr>
<tr class="even">
<td><p>C2</p></td>
<td><p>INV-1000</p></td>
<td><p>Color</p></td>
<td><p>_Red</p></td>
</tr>
<tr class="odd">
<td><p>C3</p></td>
<td><p>INV-1000</p></td>
<td><p>Color</p></td>
<td><p>&quot;Red&quot;</p></td>
</tr>
</tbody>
</table>


The items are mapped to one product, PROD-1000. The name of the Color dimension is consolidated to Red, because this name is used in C1, the company that has the highest priority.

## Company priority and product translations

When items are mapped to products, product translations are derived in the same way as dimension names and descriptions. When several items are mapped to one product, if more than one translation into a particular language exists for the items, the translations are consolidated. The translation from the company that has the highest priority is used.

## The initial company takes priority

When a mapping is completed, there is always a one-to-one relationship between items and products. Furthermore, an item is always initiated from one company. An item’s initial company is the company where the item was first created. Therefore, if you map items to existing products by aligning the product numbers in the **Product upgrade** form, the initial company always has the highest priority, regardless of how company priority is set up.

**Example**

In the previous example, product PROD-1000 inherited the dimension name from item INV-1000 in company C1, because C1 had the highest company priority. You now want to map an additional item, INV-A100, to PROD-1000. Item INV-A100 comes from another company, CA, which has a higher priority than C1. However, C1 takes precedence when properties such as the dimension name are copied to PROD-1000, because C1 is assigned as the initial company of PROD-1000. Therefore, when properties are copied, the order of priority is C1, CA, C2, and C3.

The following table shows this setup.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Company priority</p></th>
<th><p>Item</p></th>
<th><p>Initial mapping</p></th>
<th><p>Additional mapping</p></th>
<th><p>Initial company</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>CA</p></td>
<td><p>INV-A100</p></td>
<td><p></p></td>
<td><p>PROD1</p></td>
<td><p>C1</p></td>
</tr>
<tr class="even">
<td><p>C1</p></td>
<td><p>INV-1000</p></td>
<td><p>PROD1</p></td>
<td><p>PROD1</p></td>
<td><p>C1</p></td>
</tr>
<tr class="odd">
<td><p>C2</p></td>
<td><p>INV-1000</p></td>
<td><p>PROD1</p></td>
<td><p>PROD1</p></td>
<td><p>C1</p></td>
</tr>
<tr class="even">
<td><p>C3</p></td>
<td><p>INV-1000</p></td>
<td><p>PROD1</p></td>
<td><p>PROD1</p></td>
<td><p>C1</p></td>
</tr>
</tbody>
</table>



> [!TIP]
> <P>You can view the initial company of a product in the <STRONG>Company</STRONG> field on the <STRONG>Mapping</STRONG> tab of the <STRONG>Product preview</STRONG> form.</P>



## See also

[Product upgrade (preprocessing)](product-upgrade-preprocessing.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

