---
title: TransactionStatus Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transactionstatus(v=AX.60)
ms:contentKeyID: 62208031
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus.Posted
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus.Canceled
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus.Normal
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus.Voided
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus.Training
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus.OnHold
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus.Concluded
dev_langs:
- CSharp
- C++
- VB
---

# TransactionStatus Enumeration

Represents the status of Transaction/TenderLine/SalesLine.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration TransactionStatus
'Usage
Dim instance As TransactionStatus
```

``` csharp
[DataContractAttribute]
public enum TransactionStatus
```

``` c++
[DataContractAttribute]
public enum class TransactionStatus
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
<td>Normal</td>
<td>The transaction is normal.</td>
</tr>
<tr class="even">
<td></td>
<td>Voided</td>
<td>The transaction is voided.</td>
</tr>
<tr class="odd">
<td></td>
<td>Posted</td>
<td>The transaction is posted.</td>
</tr>
<tr class="even">
<td></td>
<td>Concluded</td>
<td>The transaction is concluded.</td>
</tr>
<tr class="odd">
<td></td>
<td>Canceled</td>
<td>The transaction is canceled.</td>
</tr>
<tr class="even">
<td></td>
<td>OnHold</td>
<td>The transaction is onhold.</td>
</tr>
<tr class="odd">
<td></td>
<td>Training</td>
<td>The transaction is training.</td>
</tr>
</tbody>
</table>


## Remarks

In AX, this is represented as RetailEntryStatus base enum.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

