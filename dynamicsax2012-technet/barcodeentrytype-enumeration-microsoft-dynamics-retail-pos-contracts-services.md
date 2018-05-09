---
title: BarcodeEntryType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: BarcodeEntryType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.barcodeentrytype(v=AX.60)
ms:contentKeyID: 47344097
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType.ManuallyEntered
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType.MultiScanned
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType.Selected
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType.SingleScanned
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeEntryType Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType interface specifies how the barcode was entered.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration BarcodeEntryType
'Usage
Dim instance As BarcodeEntryType
```

``` csharp
public enum BarcodeEntryType
```

``` c++
public enum class BarcodeEntryType
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
<td>Indicates whether the barcode was scanned as a single item.</td>
</tr>
<tr class="even">
<td></td>
<td>MultiScanned</td>
<td>Indicates whether the barcode was scanned with a device capable of scanning multiple items.</td>
</tr>
<tr class="odd">
<td></td>
<td>ManuallyEntered</td>
<td>Indicates whether the barcode was entered manually.</td>
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

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

