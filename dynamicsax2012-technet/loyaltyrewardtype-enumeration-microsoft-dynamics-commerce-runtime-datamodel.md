---
title: LoyaltyRewardType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyRewardType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardtype(v=AX.60)
ms:contentKeyID: 62208930
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardType.PaymentByQuantity
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardType.PaymentByAmount
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyRewardType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Describes the type of the loyalty reward.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration LoyaltyRewardType
'Usage
Dim instance As LoyaltyRewardType
```

``` csharp
[DataContractAttribute]
public enum LoyaltyRewardType
```

``` c++
[DataContractAttribute]
public enum class LoyaltyRewardType
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
<td>The default reward type. Should not be used.</td>
</tr>
<tr class="even">
<td></td>
<td>PaymentByAmount</td>
<td>Redeem reward points for payment by amount.</td>
</tr>
<tr class="odd">
<td></td>
<td>PaymentByQuantity</td>
<td>Redeem reward points for payment by quantity.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailLoyaltyRewardType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

