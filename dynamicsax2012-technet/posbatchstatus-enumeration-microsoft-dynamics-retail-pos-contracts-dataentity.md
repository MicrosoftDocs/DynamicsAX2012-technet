---
title: PosBatchStatus Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PosBatchStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.posbatchstatus(v=AX.60)
ms:contentKeyID: 47128265
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus.Suspended
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus.BlindClosed
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus.Open
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus.None
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.PosBatchStatus.Closed
dev_langs:
- CSharp
- C++
- VB
---

# PosBatchStatus Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Specifies the possible status values of a batch.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PosBatchStatus
'Usage
Dim instance As PosBatchStatus
```

``` csharp
public enum PosBatchStatus
```

``` c++
public enum class PosBatchStatus
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
<td>An invalid status. A batch is never expected to have this status.</td>
</tr>
<tr class="even">
<td></td>
<td>Open</td>
<td>The batch is open.</td>
</tr>
<tr class="odd">
<td></td>
<td>Closed</td>
<td>The batch is closed.</td>
</tr>
<tr class="even">
<td></td>
<td>BlindClosed</td>
<td>The batch is blind closed.</td>
</tr>
<tr class="odd">
<td></td>
<td>Suspended</td>
<td>The batch is suspended.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

