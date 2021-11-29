---
title: ReasonCodeInputRequiredType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonCodeInputRequiredType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputRequiredType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeinputrequiredtype(v=AX.60)
ms:contentKeyID: 62208028
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputRequiredType.Positive
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputRequiredType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputRequiredType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputRequiredType.Always
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputRequiredType.Negative
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeInputRequiredType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Input required type. Maps to RetailNoneAlwaysPositiveNegative enum in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ReasonCodeInputRequiredType
'Usage
Dim instance As ReasonCodeInputRequiredType
```

``` csharp
[DataContractAttribute]
public enum ReasonCodeInputRequiredType
```

``` c++
[DataContractAttribute]
public enum class ReasonCodeInputRequiredType
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
<td>None required = 0.</td>
</tr>
<tr class="even">
<td></td>
<td>Always</td>
<td>Always = 1.</td>
</tr>
<tr class="odd">
<td></td>
<td>Positive</td>
<td>Positive = 2.</td>
</tr>
<tr class="even">
<td></td>
<td>Negative</td>
<td>Negative = 3.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

