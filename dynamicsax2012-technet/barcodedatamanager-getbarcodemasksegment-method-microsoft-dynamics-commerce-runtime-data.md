---
title: BarcodeDataManager.GetBarcodeMaskSegment Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetBarcodeMaskSegment Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.BarcodeDataManager.GetBarcodeMaskSegment(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.barcodedatamanager.getbarcodemasksegment(v=AX.60)
ms:contentKeyID: 62213619
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.BarcodeDataManager.GetBarcodeMaskSegment
dev_langs:
- CSharp
- C++
- VB
---

# GetBarcodeMaskSegment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the barcode mask segment using the specified mask identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetBarcodeMaskSegment ( _
    maskId As String _
) As ReadOnlyCollection(Of BarcodeMaskSegment)
'Usage
Dim instance As BarcodeDataManager
Dim maskId As String
Dim returnValue As ReadOnlyCollection(Of BarcodeMaskSegment)

returnValue = instance.GetBarcodeMaskSegment(maskId)
```

``` csharp
public ReadOnlyCollection<BarcodeMaskSegment> GetBarcodeMaskSegment(
    string maskId
)
```

``` c++
public:
ReadOnlyCollection<BarcodeMaskSegment^>^ GetBarcodeMaskSegment(
    String^ maskId
)
```

#### Parameters

  - maskId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[BarcodeMaskSegment](barcodemasksegment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of barcode mask segments.  

## See Also

#### Reference

[BarcodeDataManager Class](barcodedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

