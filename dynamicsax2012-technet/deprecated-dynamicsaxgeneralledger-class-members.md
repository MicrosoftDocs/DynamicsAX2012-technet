---
title: 'Deprecated: DynamicsAXGeneralLedger class members'
TOCTitle: DynamicsAXGeneralLedger class members
ms:assetid: 34c49e16-6144-4ab4-b289-e84564714cfe
ms:mtpsurl: https://technet.microsoft.com/library/Dn507094(v=AX.60)
ms:contentKeyID: 59623180
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: DynamicsAXGeneralLedger class members 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, the **DynamicsAXGeneralLedger** class contains methods that enable specific forms to be opened in the application. Because of changes in Microsoft Dynamics AX 2012, two members have to be replaced to enable access to new functionality:

  - OpenGeneralLedgerBudgetWindow

  - OpenGeneralLedgerTransactionWindow

If these members are not replaced and are called on a AX 2012 installation, they will return failure.

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
<td><p>The data model for AX 2012 has significantly changed the interaction with certain forms and classes. The existing members of the class do not enable the required information to be passed to Microsoft Dynamics AX, so that forms can open with the correct context.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. Two new members will be added to the <strong>DynamicsAXGeneralLedger</strong> class to replace the AX 2009 functionality. The signature of these members will enable all required information to be passed, so that forms can open with the correct context.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
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

  


