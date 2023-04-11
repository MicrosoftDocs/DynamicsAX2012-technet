---
title: TransactionOperationType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionOperationType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionoperationtype(v=AX.60)
ms:contentKeyID: 62209513
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType.Delete
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType.Update
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType.Unknown
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType.Void
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType.Read
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType.Create
dev_langs:
- CSharp
- C++
- VB
---

# TransactionOperationType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the types of operations for a sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration TransactionOperationType
'Usage
Dim instance As TransactionOperationType
```

``` csharp
[DataContractAttribute]
public enum TransactionOperationType
```

``` c++
[DataContractAttribute]
public enum class TransactionOperationType
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
<td>The unknown operation.</td>
</tr>
<tr class="even">
<td></td>
<td>Create</td>
<td>The create operation.</td>
</tr>
<tr class="odd">
<td></td>
<td>Read</td>
<td>The read operation.</td>
</tr>
<tr class="even">
<td></td>
<td>Update</td>
<td>The update operation.</td>
</tr>
<tr class="odd">
<td></td>
<td>Delete</td>
<td>The delete operation.</td>
</tr>
<tr class="even">
<td></td>
<td>Void</td>
<td>The void operation.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

