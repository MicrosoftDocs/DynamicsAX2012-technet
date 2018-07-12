---
title: 'Deprecated: (IND) Per invoice option in miscellaneous charges allocation'
TOCTitle: (IND) Per invoice option in miscellaneous charges allocation
ms:assetid: fef51b09-3ebc-4870-ae86-1a50bfbf7bff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527270(v=AX.60)
ms:contentKeyID: 59623398
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (IND) Per invoice option in miscellaneous charges allocation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2009, the **Purchase order** and **Purchase invoice** headers in the **Allocate miscellaneous charges** form include a **Per invoice** option for charges. This option enables a charge to be kept on the header level, despite allocation for any subsequent invoices.

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
<td><p>In AX 2009 for Indian installations, the <strong>Purchase order</strong> and <strong>Purchase order invoice</strong> headers in the <strong>Allocate miscellaneous charges</strong> form included a <strong>Per invoice</strong> option for the <strong>Misc. charges allocation</strong> field. This option guaranteed that the same miscellaneous charge code and value were preserved on each purchase order/invoice header if a partial invoice was created for the purchase order. This option was deprecated, because Microsoft Dynamics AX 2012 provides parallel workaround functionality that lets users add miscellaneous charges for partial invoices at the header level. Therefore country-specific modifications are no longer required.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. Users can add miscellaneous charges at the invoice header level. If there are multiple invoices, the user can manually add these codes for each invoice.</p>
<p>For more information, see <a href="adjust-charges-on-vendor-invoices.md">Adjust charges on vendor invoices</a> and <a href="https://technet.microsoft.com/en-us/library/jj677929(v=ax.60)">(IND) Allocate charges (modified form)</a>.</p></td>
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

  


