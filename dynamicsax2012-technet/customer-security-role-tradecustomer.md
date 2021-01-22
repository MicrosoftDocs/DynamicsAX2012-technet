---
title: Customer security role (TradeCustomer)
TOCTitle: Customer security role (TradeCustomer)
ms:assetid: a9d10eda-6682-4eb6-8464-0a315f6f9b9f
ms:mtpsurl: https://technet.microsoft.com/library/Hh527119(v=AX.60)
ms:contentKeyID: 37823170
author: Khairunj
ms.author: daxcpft
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Customer security role (TradeCustomer) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Customer security role represents an external user who buys products from legal entities.

## Duties

By default, this security role is assigned the following duties in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty name</p></th>
<th><p>Duty AOT name</p></th>
<th><p>Duty description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Maintain customer self-service contacts master</p></td>
<td><p>EPCSSContactListMaintain</p></td>
<td><p>Document and record customer self-service contacts master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain customer self-service customer master</p></td>
<td><p>EPCSSAccountMaintain</p></td>
<td><p>Document and record customer self-service customer master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain customer service (Enterprise Portal)</p></td>
<td><p>SMAEPCustServiceMaintain</p></td>
<td><p>Maintain service related data for external customers</p></td>
</tr>
<tr class="even">
<td><p>Maintain sales orders (customer self service)</p></td>
<td><p>EPSalesSalesOrderCustSelfServiceMaintai</p></td>
<td><p>Document and record sales business events (customer self service)</p></td>
</tr>
</tbody>
</table>


## Privileges

In Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack, no privileges are directly assigned to this role. In Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3, this security role is assigned the following privileges by default.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege name</p></th>
<th><p>Privilege AOT name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Configure a product</p></td>
<td><p>EPPCConfiguratorMaintain</p></td>
</tr>
<tr class="even">
<td><p>Maintain product builder configurations (Enterprise Portal)</p></td>
<td><p>EPPBAConfiguratorMaintain</p></td>
</tr>
</tbody>
</table>

  


