---
title: NonSalesTenderType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NonSalesTenderType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.nonsalestendertype(v=AX.60)
ms:contentKeyID: 62213851
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType.RemoveTender
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType.StartingAmount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType.OpenDrawer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType.FloatEntry
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the non-sale tender type operation - starting amount / tender removal / float entry.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration NonSalesTenderType
'Usage
Dim instance As NonSalesTenderType
```

``` csharp
[DataContractAttribute]
public enum NonSalesTenderType
```

``` c++
[DataContractAttribute]
public enum class NonSalesTenderType
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
<td>No transaction type specified.</td>
</tr>
<tr class="even">
<td></td>
<td>FloatEntry</td>
<td>Float Entry is used to transfer cash to different registry.</td>
</tr>
<tr class="odd">
<td></td>
<td>StartingAmount</td>
<td>Declare start amount helps to declare starting amount when the shift is open.</td>
</tr>
<tr class="even">
<td></td>
<td>RemoveTender</td>
<td>Remove Tender.</td>
</tr>
<tr class="odd">
<td></td>
<td>OpenDrawer</td>
<td>Open Drawer.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

