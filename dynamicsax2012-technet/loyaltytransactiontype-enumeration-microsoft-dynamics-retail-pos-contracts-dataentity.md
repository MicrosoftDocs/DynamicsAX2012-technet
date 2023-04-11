---
title: LoyaltyTransactionType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyTransactionType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyTransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.loyaltytransactiontype(v=AX.60)
ms:contentKeyID: 62204997
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyTransactionType.LoyaltyAdjustment
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyTransactionType
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyTransactionType.RetailTransaction
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyTransactionType.SalesOrder
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyTransactionType.None
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTransactionType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Describes the source of the loyalty transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration LoyaltyTransactionType
'Usage
Dim instance As LoyaltyTransactionType
```

``` csharp
public enum LoyaltyTransactionType
```

``` c++
public enum class LoyaltyTransactionType
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
<td>The default transaction type. Should not be used.</td>
</tr>
<tr class="even">
<td></td>
<td>RetailTransaction</td>
<td>Retail transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>SalesOrder</td>
<td>Sales order.</td>
</tr>
<tr class="even">
<td></td>
<td>LoyaltyAdjustment</td>
<td>Loyalty adjustment.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailLoyaltyTransactionType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

