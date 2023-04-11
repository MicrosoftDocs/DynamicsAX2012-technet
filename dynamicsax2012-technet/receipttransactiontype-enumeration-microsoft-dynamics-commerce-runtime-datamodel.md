---
title: ReceiptTransactionType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptTransactionType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receipttransactiontype(v=AX.60)
ms:contentKeyID: 62213562
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType.Quote
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType.Payment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType.Return
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType.SalesOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType.Sale
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptTransactionType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the type of transaction for which the receipt is being generated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ReceiptTransactionType
'Usage
Dim instance As ReceiptTransactionType
```

``` csharp
[DataContractAttribute]
public enum ReceiptTransactionType
```

``` c++
[DataContractAttribute]
public enum class ReceiptTransactionType
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
<td>Unknown transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>Sale</td>
<td>Sales transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>Return</td>
<td>Return transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>Payment</td>
<td>Payment transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>SalesOrder</td>
<td>Sales order transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>Quote</td>
<td>Quote transaction.</td>
</tr>
</tbody>
</table>


## Remarks

This must be kept in sync with RetailReceiptTransaction Base Enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

