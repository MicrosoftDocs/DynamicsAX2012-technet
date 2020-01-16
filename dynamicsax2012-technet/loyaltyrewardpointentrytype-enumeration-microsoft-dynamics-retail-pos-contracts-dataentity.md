---
title: LoyaltyRewardPointEntryType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyRewardPointEntryType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.loyaltyrewardpointentrytype(v=AX.60)
ms:contentKeyID: 62203529
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType.Adjust
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType.Refund
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType.Redeem
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType.ReturnEarned
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType.Earn
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType.None
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyRewardPointEntryType Enumeration

Describes the entry type of the loyalty reward point line.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration LoyaltyRewardPointEntryType
'Usage
Dim instance As LoyaltyRewardPointEntryType
```

``` csharp
public enum LoyaltyRewardPointEntryType
```

``` c++
public enum class LoyaltyRewardPointEntryType
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
<td>The default entry type. Should not be used.</td>
</tr>
<tr class="even">
<td></td>
<td>Earn</td>
<td>Earn reward points.</td>
</tr>
<tr class="odd">
<td></td>
<td>Redeem</td>
<td>Redeem reward points.</td>
</tr>
<tr class="even">
<td></td>
<td>ReturnEarned</td>
<td>Return earned reward points.</td>
</tr>
<tr class="odd">
<td></td>
<td>Adjust</td>
<td>Adjust reward points.</td>
</tr>
<tr class="even">
<td></td>
<td>Refund</td>
<td>Refund reward points.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailLoyaltyRewardPointEntryType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

