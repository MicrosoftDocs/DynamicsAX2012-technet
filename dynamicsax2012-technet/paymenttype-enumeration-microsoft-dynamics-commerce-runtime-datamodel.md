---
title: PaymentType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PaymentType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.paymenttype(v=AX.60)
ms:contentKeyID: 65316783
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentType.AuthorizeOrRefund
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentType.Capture
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentType.CardToken
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentType.Unknown
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentType.Void
dev_langs:
- CSharp
- C++
- VB
---

# PaymentType Enumeration

Type of payment transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PaymentType
'Usage
Dim instance As PaymentType
```

``` csharp
public enum PaymentType
```

``` c++
public enum class PaymentType
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
<td>Unknown request (default).</td>
</tr>
<tr class="even">
<td></td>
<td>AuthorizeOrRefund</td>
<td>Authorization or refund request.</td>
</tr>
<tr class="odd">
<td></td>
<td>Void</td>
<td>Void request.</td>
</tr>
<tr class="even">
<td></td>
<td>CardToken</td>
<td>Card token request.</td>
</tr>
<tr class="odd">
<td></td>
<td>Capture</td>
<td>Capture request.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the PaymentType base enumeration in Hardware Station.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

