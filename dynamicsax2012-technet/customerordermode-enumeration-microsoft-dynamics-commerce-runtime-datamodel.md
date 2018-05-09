---
title: CustomerOrderMode Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerOrderMode Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customerordermode(v=AX.60)
ms:contentKeyID: 62208496
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode.Return
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode.Cancellation
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode.Pickup
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode.CustomerOrderCreateOrEdit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode.QuoteCreateOrEdit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode.OrderRecalled
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderMode Enumeration

Represents the different operations that can be done over a customer order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CustomerOrderMode
'Usage
Dim instance As CustomerOrderMode
```

``` csharp
public enum CustomerOrderMode
```

``` c++
public enum class CustomerOrderMode
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
<td>Customer order mode not set.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerOrderCreateOrEdit</td>
<td>A customer order creation or edition.</td>
</tr>
<tr class="odd">
<td></td>
<td>OrderRecalled</td>
<td>A customer order that bas been recalled but not yet operated on.</td>
</tr>
<tr class="even">
<td></td>
<td>Pickup</td>
<td>A pick up at store operation.</td>
</tr>
<tr class="odd">
<td></td>
<td>Return</td>
<td>A customer order return.</td>
</tr>
<tr class="even">
<td></td>
<td>Cancellation</td>
<td>The cancellation of a customer order.</td>
</tr>
<tr class="odd">
<td></td>
<td>QuoteCreateOrEdit</td>
<td>The creation or edition of a quote.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

