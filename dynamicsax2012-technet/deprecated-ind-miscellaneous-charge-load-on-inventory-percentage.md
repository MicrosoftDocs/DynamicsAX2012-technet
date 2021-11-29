---
title: 'Deprecated: (IND) Miscellaneous charge load on inventory percentage'
TOCTitle: (IND) Miscellaneous charge load on inventory percentage
ms:assetid: 319d14c2-8292-4e0b-98f7-1f9330d0192f
ms:mtpsurl: https://technet.microsoft.com/library/Dn507089(v=AX.60)
ms:contentKeyID: 59623179
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (IND) Miscellaneous charge load on inventory percentage 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2009 lets users post a specified percentage (partial amount) of a miscellaneous charge to inventory. The remaining miscellaneous charge is charged to the vendor or customer.

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
<td><p>In AX 2009, the <strong>Load on inventory %</strong> field is a country-specific feature for India. This field lets users to split the miscellaneous charges that are added to an invoice between inventory and the vendor or customer. Foundational changes that were made for Microsoft Dynamics AX 2012 made this country-specific option redundant.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. In AX 2012, users can create two standard charge codes to achieve the same business impact. When creating charge codes on the <strong>Charges code</strong> form, users can set up one charge code that has the <strong>Debit</strong> <strong>Type</strong> field set to <strong>Item</strong> and another charge that has <strong>Debit</strong> <strong>Type</strong> set to <strong>Customer/Vendor</strong>. When users create the invoice, they can split the miscellaneous charge amount between these two charge codes. The <strong>Allocate charges</strong> form lets users divide the amount that is charged to the item, customer, or vendor, based on the percentage that is specified. For example, a charge that has <strong>Debit</strong> <strong>Type</strong> set to <strong>Item</strong> receives 10 percent, and a charge that has <strong>Debit</strong> <strong>Type</strong> set to <strong>Customer/Vendor</strong> receives 90 percent.</p>
<p>For more information, see <a href="create-charges-codes.md">Create charges codes</a>, <a href="adjust-charges-on-vendor-invoices.md">Adjust charges on vendor invoices</a>, and <a href="https://technet.microsoft.com/library/jj677929(v=ax.60)">(IND) Allocate charges (modified form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Accounts payable</p></td>
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

  


