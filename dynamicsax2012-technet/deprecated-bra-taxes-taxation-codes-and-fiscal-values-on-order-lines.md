---
title: 'Deprecated: (BRA) Taxes, taxation codes, and fiscal values on order lines'
TOCTitle: (BRA) Taxes, taxation codes, and fiscal values on order lines
ms:assetid: d93696f5-aee8-4a46-ac6f-58ae5c7ee4eb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527223(v=AX.60)
ms:contentKeyID: 59623351
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) Taxes, taxation codes, and fiscal values on order lines 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Brazilian installations, Microsoft Dynamics AX 2009 provides country-specific functionality that supports modification of the taxation codes and fiscal values for purchase order and sales orders lines per sales tax code.

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
<td><p>The capability to change the taxation codes and fiscal values for purchase and sales order lines was rarely used in sales orders, where the taxes that are set up can be determined before the sales order is created. This capability was also not often used in purchase orders, because the changes are captured and required when the fiscal document is received.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. Microsoft Dynamics AX 2012 supports the modification of taxation codes and fiscal values through the tax adjustment feature that is available when a fiscal document is posted.</p>
<p>For more information, see <a href="bra-create-and-post-a-purchase-complementary-fiscal-document.md">(BRA) Create and post a purchase complementary fiscal document</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Accounts payable</p>
<p>Accounts receivable</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>This change does not affect application upgrade.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

