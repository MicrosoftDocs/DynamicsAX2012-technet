---
title: CardType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtype(v=AX.60)
ms:contentKeyID: 62214094
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.CustomerCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.InternationalDebitCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.CorporateCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.GiftCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.InternationalCreditCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.EmployeeCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.SalespersonCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.Unknown
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType.LoyaltyCard
dev_langs:
- CSharp
- C++
- VB
---

# CardType Enumeration

List of card types supported by the system.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CardType
'Usage
Dim instance As CardType
```

``` csharp
public enum CardType
```

``` c++
public enum class CardType
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
<td>Unknown</td>
<td>Unspecified card type.</td>
</tr>
<tr class="even">
<td></td>
<td>InternationalCreditCard</td>
<td>International cards - Brokered by an EFT Service Provider.</td>
</tr>
<tr class="odd">
<td></td>
<td>InternationalDebitCard</td>
<td>International cards - Brokered by an EFT Service Provider.</td>
</tr>
<tr class="even">
<td></td>
<td>LoyaltyCard</td>
<td>Loyalty cards.</td>
</tr>
<tr class="odd">
<td></td>
<td>CorporateCard</td>
<td>Local corporate credit cards.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerCard</td>
<td>Customer card - used to identify customers.</td>
</tr>
<tr class="odd">
<td></td>
<td>EmployeeCard</td>
<td>Employee card - used to log employees on the pos.</td>
</tr>
<tr class="even">
<td></td>
<td>SalespersonCard</td>
<td>Salesperson card - used to identify salespersons.</td>
</tr>
<tr class="odd">
<td></td>
<td>GiftCard</td>
<td>Gift card - used to identify the customers gift card.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the RetailCardTypeBase base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

