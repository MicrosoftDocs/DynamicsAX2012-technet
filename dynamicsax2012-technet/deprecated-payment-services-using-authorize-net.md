---
title: 'Deprecated: Payment services using Authorize.net'
TOCTitle: Payment services using Authorize.net
ms:assetid: edde8971-717c-45f4-8719-01751afdefd7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527231(v=AX.60)
ms:contentKeyID: 59623359
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Payment services using Authorize.net 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, we introduced integration with two payment services: Authorize.Net and Payment Services for Microsoft Dynamics ERP. Microsoft Dynamics AX 2012 supports only Payment Services.

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
<td><p>Cybersource has purchased Authorize.Net, and we anticipate that Authorize.Net services will eventually be integrated into Cybersource’s suite of products. AX 2012 offers a single point of access to Cybersource through Payment Services.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>No. The feature is no longer available, and there is no replacement for it.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Accounts payable</p>
<p>Accounts receivable</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>The installation of AX 2012 will not change. However, Authorize.Net will no longer appear as a valid payment service.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Customers can switch from Authorize.Net to Payment Services. After a customer obtains a Payment Services account, AX 2009 will continue to use Authorize.Net to process existing sales orders that use credit cards which have been authorized by Authorize.Net. However, all new orders will be processed by using Payment Services. For more information, see the whitepaper titled <a href="http://www.microsoft.com/en-us/download/confirmation.aspx?id=28157">Microsoft Dynamics AX 2009 Hotfix White Paper: Credit Card Processing</a>.</p></td>
</tr>
</tbody>
</table>

  


