---
title: CartType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CartType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.carttype(v=AX.60)
ms:contentKeyID: 62212846
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType.Checkout
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType.CustomerOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType.IncomeExpense
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType.Shopping
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType.AccountDeposit
dev_langs:
- CSharp
- C++
- VB
---

# CartType Enumeration

Represents the shopping cart type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration CartType
'Usage
Dim instance As CartType
```

``` csharp
[DataContractAttribute]
public enum CartType
```

``` c++
[DataContractAttribute]
public enum class CartType
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
<td>None (Cart Type not defined).</td>
</tr>
<tr class="even">
<td></td>
<td>Shopping</td>
<td>Shopping cart.</td>
</tr>
<tr class="odd">
<td></td>
<td>Checkout</td>
<td>Checkout cart - The temporary copy of the shopping cart created during the checkout process.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerOrder</td>
<td>Cart represents a customer order.</td>
</tr>
<tr class="odd">
<td></td>
<td>IncomeExpense</td>
<td>Cart represents a IncomeExpense account transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>AccountDeposit</td>
<td></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

