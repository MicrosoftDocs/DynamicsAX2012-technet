---
title: Set up product search options
TOCTitle: Set up product search options
ms:assetid: c61118c1-e2c0-4dbd-a3d3-f2da7e031364
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497825(v=AX.60)
ms:contentKeyID: 62200155
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRSalesQuickQuote
- Forms.MCRFullTextIndexField
- Forms.MCRFullTextParameters
- item search
- product search
- product availability
- search for products
audience: Application User
ms.search.region: Global
---

# Set up product search options 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to configure full-text searches for products in the **Sales order** form. After you define search criteria and parameters, users can enter search terms in the **Item number** field of the **Sales order** form to perform a full-text search of the product database. The search results show the products that match the search terms. The results also show availability information for each product.

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
<td><p>Set up products</p></td>
<td><p><a href="setting-up-retail-products.md">Setting up retail products</a></p></td>
</tr>
</tbody>
</table>


## Set up search criteria

You must specify which database fields to include in the search. You must also set parameters that specify how the search results are handled.

To set up search criteria for products, follow these steps.

1.  Click **Sales and marketing** \> **Setup** \> **Search** \> **Define criteria** .

2.  In the **Define criteria** form, in the **Type** field, select **Item**.

3.  On the **Action Pane**, click **New**.

4.  The **View or table** field is set to **MCRProductSearchView**. In the **Field name** field, select a field to search in the **MCRProductSearchView** view.

5.  Continue to add field names as you require. At a minimum, effective searches require the following fields:
    
      - **ItemID**
    
      - **NameAlias**
    
      - **ProductName**

6.  On the **Action Pane**, click **Refresh** to update the entries in the search index table.

7.  Click **Sales and marketing** \> **Setup** \> **Search** \> **Search parameters**.

8.  In the **Search parameters** form, set the options as you require. For example, enter information about the number of search results to return, and specify whether search terms can be partially matched.

9.  Optional: In the product details for an individual product, you can associate a search term with the product. For more information, see [Released product details (form)](https://technet.microsoft.com/en-us/library/aa615563\(v=ax.60\)).

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
<td><p><strong>Trade</strong> configuration key</p>
<p><strong>Full text search</strong> configuration key</p>
<p><strong>Trade item search</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager (to set up search criteria)</p>
<p>Sales clerk (to create a sales order)</p></td>
</tr>
</tbody>
</table>


## See also

Create a sales order in Call center

  


