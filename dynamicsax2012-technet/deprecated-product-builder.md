---
title: 'Deprecated: Product builder'
TOCTitle: Product builder
ms:assetid: e30e2377-f85d-4703-9398-f382ebd87629
ms:mtpsurl: https://technet.microsoft.com/library/Dn527253(v=AX.60)
ms:contentKeyID: 59623381
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Product builder 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, users can use Product builder to create product models that can be used in a configure-to-order scenario.

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
<td><p>In AX 2009, Product builder uses X++ to write rules and restrictions that apply to product models. Therefore, there is potential risk of elevation of privilege. Additionally, the design of Product builder does not scale well when the models grow in size. Therefore, there are long response times during product configuration on sales order lines.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Product builder will still be available for existing Product builder customers that upgrade to Microsoft Dynamics AX 2012, but not for new customers. In AX 2012, Product builder was replaced with the Product configuration feature, which is constraint-based instead of rule-based. The Product configuration feature provides better support for reusability and multilevel product models. It also performs better than Product builder and eliminates security threats that involve elevation of privilege.</p>
<p>For more information, see <a href="setting-up-and-maintaining-product-configurations.md">Setting up and maintaining product configurations</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Sales and marketing</p>
<p>Enterprise Portal for Microsoft Dynamics AX</p>
<p>Project management and accounting</p>
<p>Product information management</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>For existing Product builder customers, the existing Product models are upgraded as usual. Product builder models can be upgraded to Product configuration models. To upgrade a Product builder model, you must analyze the back-end tree of the Product builder model to identify those elements that should be included directly in the Product configuration model and those that must be implemented by using the dedicated product configuration API, PCAdaptor.</p></td>
</tr>
</tbody>
</table>

  


