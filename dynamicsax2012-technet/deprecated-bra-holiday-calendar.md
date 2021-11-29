---
title: 'Deprecated: (BRA) Holiday calendar'
TOCTitle: (BRA) Holiday calendar
ms:assetid: 3d8dcf35-c327-4668-acdd-af8d5c602b32
ms:mtpsurl: https://technet.microsoft.com/library/Dn507107(v=AX.60)
ms:contentKeyID: 59623197
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) Holiday calendar 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2009 includes the Holiday calendar, which is a country-specific feature for Brazilian installations. The Holiday calendar is used to identify a company’s non-working days or holidays when invoice due dates are calculated. For late payments, the Holiday calendar is also used to calculate the interest and fines that are applied at the time of payment. Because Microsoft Dynamics AX 2012 R2 includes Payment calendar functionality, country-specific modifications are not required.

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
<td><p>AX 2012 R2 includes Payment calendar functionality. Therefore, the Holiday calendar is no longer required.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. AX 2012 R2 includes a Payment calendar feature that lets users define non-working days or holidays that are used to determine invoice due dates. For late payments, the Payment calendar is also used to calculate interest and fines at the time of payment.</p>
<p>For more information, see <a href="set-up-a-payment-calendar-and-payment-calendar-rules.md">Set up a payment calendar and payment calendar rules</a>.</p></td>
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
<td><p>Upgrade scripts are provided that migrate existing Holiday calendar data to the new Payment calendar feature.</p></td>
</tr>
</tbody>
</table>

  


