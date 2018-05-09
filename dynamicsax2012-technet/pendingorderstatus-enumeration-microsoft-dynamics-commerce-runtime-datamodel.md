---
title: PendingOrderStatus Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PendingOrderStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PendingOrderStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.pendingorderstatus(v=AX.60)
ms:contentKeyID: 62211516
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PendingOrderStatus
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PendingOrderStatus.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PendingOrderStatus.Failed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PendingOrderStatus.Succeeded
dev_langs:
- CSharp
- C++
- VB
---

# PendingOrderStatus Enumeration

The status of a pending order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration PendingOrderStatus
'Usage
Dim instance As PendingOrderStatus
```

``` csharp
[DataContractAttribute]
public enum PendingOrderStatus
```

``` c++
[DataContractAttribute]
public enum class PendingOrderStatus
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
<td>Unknown = 0.</td>
</tr>
<tr class="even">
<td></td>
<td>Failed</td>
<td>Failed = 1.</td>
</tr>
<tr class="odd">
<td></td>
<td>Succeeded</td>
<td>Succeeded = 2.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

