---
title: LoyaltyTransactionType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyTransactionType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltytransactiontype(v=AX.60)
ms:contentKeyID: 62205149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTransactionType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTransactionType.LoyaltyAdjustment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTransactionType.RetailTransaction
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTransactionType.SalesOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTransactionType
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTransactionType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Describes the source of the loyalty transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration LoyaltyTransactionType
'Usage
Dim instance As LoyaltyTransactionType
```

``` csharp
[DataContractAttribute]
public enum LoyaltyTransactionType
```

``` c++
[DataContractAttribute]
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

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

