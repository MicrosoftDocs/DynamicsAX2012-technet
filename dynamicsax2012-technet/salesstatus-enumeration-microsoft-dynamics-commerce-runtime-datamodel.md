---
title: SalesStatus Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesstatus(v=AX.60)
ms:contentKeyID: 49839120
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Canceled
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Confirmed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Created
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Delivered
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Invoiced
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Lost
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Processing
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Sent
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus.Unknown
dev_langs:
- CSharp
- C++
- VB
---

# SalesStatus Enumeration

Aggregated AX Sales Order status values

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration SalesStatus
'Usage
Dim instance As SalesStatus
```

``` csharp
[DataContractAttribute]
public enum SalesStatus
```

``` c++
[DataContractAttribute]
public enum class SalesStatus
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
<td>Unknown = 0</td>
</tr>
<tr class="even">
<td></td>
<td>Created</td>
<td>Created = 1</td>
</tr>
<tr class="odd">
<td></td>
<td>Processing</td>
<td>Processing = 2</td>
</tr>
<tr class="even">
<td></td>
<td>Delivered</td>
<td>Delivered = 3,</td>
</tr>
<tr class="odd">
<td></td>
<td>Invoiced</td>
<td>Invoiced = 4</td>
</tr>
<tr class="even">
<td></td>
<td>Confirmed</td>
<td>Confirmed = 5</td>
</tr>
<tr class="odd">
<td></td>
<td>Sent</td>
<td>Sent = 6</td>
</tr>
<tr class="even">
<td></td>
<td>Canceled</td>
<td>Canceled = 7</td>
</tr>
<tr class="odd">
<td></td>
<td>Lost</td>
<td>Lost = 8</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the RetailSalesType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

