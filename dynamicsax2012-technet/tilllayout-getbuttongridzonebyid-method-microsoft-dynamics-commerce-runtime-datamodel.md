---
title: TillLayout.GetButtonGridZoneById Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetButtonGridZoneById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.GetButtonGridZoneById(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.getbuttongridzonebyid(v=AX.60)
ms:contentKeyID: 62212544
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.GetButtonGridZoneById
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGridZoneById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets button grid zone by zone id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetButtonGridZoneById ( _
    zoneId As String _
) As ButtonGridZone
'Usage
Dim instance As TillLayout
Dim zoneId As String
Dim returnValue As ButtonGridZone

returnValue = instance.GetButtonGridZoneById(zoneId)
```

``` csharp
public ButtonGridZone GetButtonGridZoneById(
    string zoneId
)
```

``` c++
public:
ButtonGridZone^ GetButtonGridZoneById(
    String^ zoneId
)
```

#### Parameters

  - zoneId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridZone](buttongridzone-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Button grid zone.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

