---
title: BlockedEnum Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BlockedEnum Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.BlockedEnum
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.blockedenum(v=AX.60)
ms:contentKeyID: 47128594
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.BlockedEnum
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.BlockedEnum.Invoice
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.BlockedEnum.No
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.BlockedEnum.All
dev_langs:
- CSharp
- C++
- VB
---

# BlockedEnum Enumeration

The different types of blocking the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration BlockedEnum
'Usage
Dim instance As BlockedEnum
```

``` csharp
public enum BlockedEnum
```

``` c++
public enum class BlockedEnum
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
<td>No</td>
<td>No blocking. The customer can be charged and invoiced.</td>
</tr>
<tr class="even">
<td></td>
<td>Invoice</td>
<td>The customer can be selected but not invoiced.</td>
</tr>
<tr class="odd">
<td></td>
<td>All</td>
<td>The customer cannot be added to a transaction.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

