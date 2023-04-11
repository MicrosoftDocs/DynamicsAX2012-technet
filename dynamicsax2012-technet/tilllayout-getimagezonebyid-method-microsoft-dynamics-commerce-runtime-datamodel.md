---
title: TillLayout.GetImageZoneById Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetImageZoneById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.GetImageZoneById(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.getimagezonebyid(v=AX.60)
ms:contentKeyID: 62214260
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.GetImageZoneById
dev_langs:
- CSharp
- C++
- VB
---

# GetImageZoneById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets image zone by zone id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetImageZoneById ( _
    zoneId As String _
) As ImageZone
'Usage
Dim instance As TillLayout
Dim zoneId As String
Dim returnValue As ImageZone

returnValue = instance.GetImageZoneById(zoneId)
```

``` csharp
public ImageZone GetImageZoneById(
    string zoneId
)
```

``` c++
public:
ImageZone^ GetImageZoneById(
    String^ zoneId
)
```

#### Parameters

  - zoneId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ImageZone](imagezone-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Image zone.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

