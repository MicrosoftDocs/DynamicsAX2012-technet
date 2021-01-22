---
title: BarcodeEntryMethodType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BarcodeEntryMethodType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeEntryMethodType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodeentrymethodtype(v=AX.60)
ms:contentKeyID: 62208115
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeEntryMethodType.Selected
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeEntryMethodType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeEntryMethodType.SingleScanned
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeEntryMethodType.MultipleScanned
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeEntryMethodType.ManuallyEntered
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeEntryMethodType Enumeration

Describes, how the barcode was entered. See member list for details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration BarcodeEntryMethodType
'Usage
Dim instance As BarcodeEntryMethodType
```

``` csharp
public enum BarcodeEntryMethodType
```

``` c++
public enum class BarcodeEntryMethodType
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
<td>SingleScanned</td>
<td>Was the barcode scanned as a single item.</td>
</tr>
<tr class="even">
<td></td>
<td>MultipleScanned</td>
<td>Was the barcode scanned with a device capable of scanning multiple items.</td>
</tr>
<tr class="odd">
<td></td>
<td>ManuallyEntered</td>
<td>Was the barcode manually entered.</td>
</tr>
<tr class="even">
<td></td>
<td>Selected</td>
<td>Selected from a button or a screen.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

