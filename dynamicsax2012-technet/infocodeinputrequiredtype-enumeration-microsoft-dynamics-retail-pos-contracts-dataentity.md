---
title: InfoCodeInputRequiredType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InfoCodeInputRequiredType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputRequiredType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.infocodeinputrequiredtype(v=AX.60)
ms:contentKeyID: 47129319
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputRequiredType
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputRequiredType.PositiveAndNegative
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputRequiredType.Negative
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputRequiredType.Positive
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputRequiredType.Always
dev_langs:
- CSharp
- C++
- VB
---

# InfoCodeInputRequiredType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This enum is used to determine when an Infocode is required.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration InfoCodeInputRequiredType
'Usage
Dim instance As InfoCodeInputRequiredType
```

``` csharp
public enum InfoCodeInputRequiredType
```

``` c++
public enum class InfoCodeInputRequiredType
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
<td>Always</td>
<td>The Infocode is always required.</td>
</tr>
<tr class="even">
<td></td>
<td>PositiveAndNegative</td>
<td>The Infocode is applicable for both positive and negative quantities.</td>
</tr>
<tr class="odd">
<td></td>
<td>Positive</td>
<td>The Infocode is only applicable for positive quantities.</td>
</tr>
<tr class="even">
<td></td>
<td>Negative</td>
<td>The Infocode is only applicable for negative quantities.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

