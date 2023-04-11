---
title: AttributeDataType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeDataType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributedatatype(v=AX.60)
ms:contentKeyID: 49846344
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.Currency
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.DateTime
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.Decimal
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.Integer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.Text
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.TrueFalse
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.Image
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType.Video
dev_langs:
- CSharp
- C++
- VB
---

# AttributeDataType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the data type of the attribute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration AttributeDataType
'Usage
Dim instance As AttributeDataType
```

``` csharp
public enum AttributeDataType
```

``` c++
public enum class AttributeDataType
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
<td>No attribute data type specified.</td>
</tr>
<tr class="even">
<td></td>
<td>Currency</td>
<td>An attribute of type currency.</td>
</tr>
<tr class="odd">
<td></td>
<td>DateTime</td>
<td>An attribute of type date time.</td>
</tr>
<tr class="even">
<td></td>
<td>Decimal</td>
<td>An attribute of type decimal.</td>
</tr>
<tr class="odd">
<td></td>
<td>Integer</td>
<td>An attribute of type integer.</td>
</tr>
<tr class="even">
<td></td>
<td>Text</td>
<td>An attribute of type string.</td>
</tr>
<tr class="odd">
<td></td>
<td>TrueFalse</td>
<td>An attribute of type boolean.</td>
</tr>
<tr class="even">
<td></td>
<td>Video</td>
<td>An attribute of video type media.</td>
</tr>
<tr class="odd">
<td></td>
<td>Image</td>
<td>An attribute of image type media.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the AttributeDataType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

