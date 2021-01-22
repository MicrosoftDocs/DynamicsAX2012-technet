---
title: BarcodeDataManager.GetBarcodeMask Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetBarcodeMask Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.BarcodeDataManager.GetBarcodeMask(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.barcodedatamanager.getbarcodemask(v=AX.60)
ms:contentKeyID: 62202086
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.BarcodeDataManager.GetBarcodeMask
dev_langs:
- CSharp
- C++
- VB
---

# GetBarcodeMask Method

Gets the barcode mask using the specified prefix.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetBarcodeMask ( _
    prefix As String _
) As ReadOnlyCollection(Of BarcodeMask)
'Usage
Dim instance As BarcodeDataManager
Dim prefix As String
Dim returnValue As ReadOnlyCollection(Of BarcodeMask)

returnValue = instance.GetBarcodeMask(prefix)
```

``` csharp
public ReadOnlyCollection<BarcodeMask> GetBarcodeMask(
    string prefix
)
```

``` c++
public:
ReadOnlyCollection<BarcodeMask^>^ GetBarcodeMask(
    String^ prefix
)
```

#### Parameters

  - prefix  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[BarcodeMask](barcodemask-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of barcode masks matching the specified prefix.  

## See Also

#### Reference

[BarcodeDataManager Class](barcodedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

