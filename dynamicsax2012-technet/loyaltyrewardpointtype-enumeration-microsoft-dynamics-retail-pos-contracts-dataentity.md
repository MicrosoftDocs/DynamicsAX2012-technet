---
title: LoyaltyRewardPointType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyRewardPointType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.loyaltyrewardpointtype(v=AX.60)
ms:contentKeyID: 62204839
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointType
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointType.None
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointType.Quantity
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointType.Amount
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyRewardPointType Enumeration

Describes the unit type of the loyalty reward point.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration LoyaltyRewardPointType
'Usage
Dim instance As LoyaltyRewardPointType
```

``` csharp
public enum LoyaltyRewardPointType
```

``` c++
public enum class LoyaltyRewardPointType
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>The default reward point type. Should not be used.</td>
</tr>
<tr class="even">
<td></td>
<td>Quantity</td>
<td>Quantity type measured by a numeric value.</td>
</tr>
<tr class="odd">
<td></td>
<td>Amount</td>
<td>Amount type measured by a numeric value and a currency code.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailLoyaltyRewardPointType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

