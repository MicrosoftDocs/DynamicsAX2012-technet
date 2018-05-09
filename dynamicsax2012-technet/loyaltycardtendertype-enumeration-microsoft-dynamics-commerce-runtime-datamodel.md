---
title: LoyaltyCardTenderType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyCardTenderType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtendertype(v=AX.60)
ms:contentKeyID: 62214865
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType.NoTender
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType.AsContactTender
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType.Blocked
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType.AsCardTender
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTenderType Enumeration

Describes the tender type of the loyalty card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration LoyaltyCardTenderType
'Usage
Dim instance As LoyaltyCardTenderType
```

``` csharp
[DataContractAttribute]
public enum LoyaltyCardTenderType
```

``` c++
[DataContractAttribute]
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

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

