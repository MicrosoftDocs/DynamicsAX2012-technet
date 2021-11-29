---
title: PriceDiscountAccountCode Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceDiscountAccountCode Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pricediscountaccountcode(v=AX.60)
ms:contentKeyID: 49830750
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode.AllCustomers
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode.Customer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode.CustomerGroup
dev_langs:
- CSharp
- C++
- VB
---

# PriceDiscountAccountCode Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Enables to grant a discount with regard to a customer, a superordinate customer group or to all customers.

Refers to table PriceDiscTable.AccountCode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PriceDiscountAccountCode
'Usage
Dim instance As PriceDiscountAccountCode
```

``` csharp
public enum PriceDiscountAccountCode
```

``` c++
public enum class PriceDiscountAccountCode
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
<td>Customer</td>
<td>An account code associated to a customer.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerGroup</td>
<td>An account code associated to a customer group.</td>
</tr>
<tr class="odd">
<td></td>
<td>AllCustomers</td>
<td>An account code associated to all customers.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the TableGroupAll enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

