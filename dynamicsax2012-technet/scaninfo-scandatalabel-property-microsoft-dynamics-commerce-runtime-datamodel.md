---
title: ScanInfo.ScanDataLabel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ScanDataLabel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ScanInfo.ScanDataLabel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.scaninfo.scandatalabel(v=AX.60)
ms:contentKeyID: 62209856
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ScanInfo.ScanDataLabel
dev_langs:
- CSharp
- C++
- VB
---

# ScanDataLabel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the striped barcode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property ScanDataLabel As String
    Get
    Set
'Usage
Dim instance As ScanInfo
Dim value As String

value = instance.ScanDataLabel

instance.ScanDataLabel = value
```

``` csharp
public string ScanDataLabel { get; set; }
```

``` c++
public:
property String^ ScanDataLabel {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ScanInfo Class](scaninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

