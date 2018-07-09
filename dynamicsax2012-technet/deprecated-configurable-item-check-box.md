---
title: 'Deprecated: Configurable item check box'
TOCTitle: Configurable item check box
ms:assetid: e15c1e6c-394b-48e7-a1ee-7502aeaee011
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527227(v=AX.60)
ms:contentKeyID: 59623355
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Configurable item check box [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, a check box controls whether an item can be configured.

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
<td><p>Architectural changes in Microsoft Dynamics AX 2012 changed the way that products are defined.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed, and a replacement feature is available. As part of the new product definition concept in AX 2012, the process of defining a product has been made more explicit. Users select whether a product is a simple product or a product master. If a product is a product master, the user must specify the tool or method that is used to create product variants for that master.</p>
<p>For more information, see <a href="product-information-management.md">Product information management</a>. For more information about item-product management, see the white paper <a href="http://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_item-product_data_management_framework_for_microsoft_dynamics_ax_2012_applications_ax2012.pdf">Implementing the Item-Product Data Management Framework</a>.</p></td>
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
<td><p>During the upgrade from AX 2009 to AX 2012, configurable items are upgraded according to product master rules and are upgraded to product masters by using dimension-based configuration.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

