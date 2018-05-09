---
title: LoyaltyCardTenderType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyCardTenderType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyCardTenderType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.loyaltycardtendertype(v=AX.60)
ms:contentKeyID: 62204116
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyCardTenderType.Blocked
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyCardTenderType.AsCardTender
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyCardTenderType
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyCardTenderType.AsContactTender
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyCardTenderType.NoTender
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTenderType Enumeration

Describes the tender type of the loyalty card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration LoyaltyCardTenderType
'Usage
Dim instance As LoyaltyCardTenderType
```

``` csharp
public enum LoyaltyCardTenderType
```

``` c++
public enum class LoyaltyCardTenderType
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
<td>AsCardTender</td>
<td>The defult value indicating the card can only redeem reward points that are earned on itself.</td>
</tr>
<tr class="even">
<td></td>
<td>AsContactTender</td>
<td>The card can redeem reward points that are earned on any cards of the same customer.</td>
</tr>
<tr class="odd">
<td></td>
<td>NoTender</td>
<td>The card can only earn reward points but not redeem.</td>
</tr>
<tr class="even">
<td></td>
<td>Blocked</td>
<td>The card is blocked.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailLoyaltyTenderTypeBase base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

