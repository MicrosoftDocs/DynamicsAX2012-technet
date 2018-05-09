---
title: 'Deprecated: Support for BOM item type BOM'
TOCTitle: BOM item type BOM
ms:assetid: 718e3957-b77a-4779-bd6d-81460fe6066b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527142(v=AX.60)
ms:contentKeyID: 59623271
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Support for BOM item type BOM 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, a bill of materials (BOM) can be associated only with items of the BOM item type.

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
<td><p>Reason for deprecation</p></td>
<td><p>Architectural changes in Microsoft Dynamics AX 2012 have changed the way that items are defined. Items have become products, and products require a product definition. The product definition consists of a few core characteristics that help identify the product. One characteristic is the product type, which indicates whether a product is tangible (an item) or intangible (a service or rights). In AX 2009, the item type indicated whether the product was tangible (an item) or intangible (a service), and also the role that the item could have (BOM). To guarantee that characteristics are product-related, not product role–related, the item type attribute was refactored to product type, and the BOM value was separated from the item and service values.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed, and a replacement feature is available. Users must still be able to associate a BOM with a product of the item type. Therefore, in AX 2012, customers can associate a BOM with a product of the item type. After this association is made, users can use the new default order type on the default order settings to indicate whether the item that has an associated BOM must be procured or manufactured.</p>
<p>For more information, see <a href="setting-up-and-maintaining-bills-of-materials.md">Setting up and maintaining bills of materials</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Inventory management</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>User who upgrade from AX 2009 to AX 2012 must map existing items to new product definitions. As part of this process, they must decide whether the default order type is purchase or production. The association with a BOM is maintained.</p></td>
</tr>
</tbody>
</table>


For more information about item-product management, see the white paper [Implementing the Item-Product data management framework for Microsoft Dynamics AX 2012 Applications](http://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_item-product_data_management_framework_for_microsoft_dynamics_ax_2012_applications_ax2012.pdf).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

