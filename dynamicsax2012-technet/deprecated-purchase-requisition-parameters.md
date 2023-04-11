---
title: 'Deprecated: Purchase requisition parameters'
TOCTitle: Purchase requisition parameters
ms:assetid: 2ad9007a-b0ab-4d78-9f17-02dc84179c02
ms:mtpsurl: https://technet.microsoft.com/library/Dn527119(v=AX.60)
ms:contentKeyID: 59623248
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Purchase requisition parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, purchase requisition setup is managed on the **Purchase requisition** tab of the **Setup parameters** form in **Accounts payable**.

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
<td><p>All parameters that are related to purchasing are now included in Purchasing policy rules.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The Purchase requisition control policy rule contains the parameters that define which fields are required for a purchase requisition to be submitted to workflow. This policy rule also contains the parameters that define whether minimum, maximum, and multiple quantity constraints are enforced.</p>
<p>The Purchase requisition to purchase order creation policy rule contains the parameters that define when purchase orders are generated automatically by the system.</p>
<p>For more information, see <a href="about-purchasing-policies.md">About purchasing policies</a> and the <a href="https://go.microsoft.com/fwlink/?linkid=213137%26clcid=0x409">Using the Policy Framework in Microsoft Dynamics AX 2012</a> white paper.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Procurement and sourcing</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Any product groups that are used in AX 2009 must be upgraded to procurement categories. Additionally, any product and category catalogs that are used in AX 2009 must be upgraded to procurement catalogs. Catalog policy rules and Category access policy rules can be used to scope the products and procurement categories that are available in different legal entities.</p></td>
</tr>
</tbody>
</table>

  


