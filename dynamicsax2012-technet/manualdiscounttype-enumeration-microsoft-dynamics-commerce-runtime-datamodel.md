---
title: ManualDiscountType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ManualDiscountType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ManualDiscountType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.manualdiscounttype(v=AX.60)
ms:contentKeyID: 62209920
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ManualDiscountType.LineDiscountAmount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ManualDiscountType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ManualDiscountType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ManualDiscountType.TotalDiscountAmount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ManualDiscountType.TotalDiscountPercent
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ManualDiscountType.LineDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# ManualDiscountType Enumeration

Type of manual discount represents Enum RetailManualDiscountType in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ManualDiscountType
'Usage
Dim instance As ManualDiscountType
```

``` csharp
[DataContractAttribute]
public enum ManualDiscountType
```

``` c++
[DataContractAttribute]
public enum class ManualDiscountType
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
<td>Not manual discount.</td>
</tr>
<tr class="even">
<td></td>
<td>LineDiscountAmount</td>
<td>A single line discount amount.</td>
</tr>
<tr class="odd">
<td></td>
<td>LineDiscountPercent</td>
<td>A single line discount percent.</td>
</tr>
<tr class="even">
<td></td>
<td>TotalDiscountAmount</td>
<td>A total discount amount.</td>
</tr>
<tr class="odd">
<td></td>
<td>TotalDiscountPercent</td>
<td>A total discount percent.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

