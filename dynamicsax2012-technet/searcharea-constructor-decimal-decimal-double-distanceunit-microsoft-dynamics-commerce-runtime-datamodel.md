---
title: SearchArea Constructor (Decimal, Decimal, Double, DistanceUnit) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchArea Constructor (Decimal, Decimal, Double, DistanceUnit)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.#ctor(System.Decimal,System.Decimal,System.Double,Microsoft.Dynamics.Commerce.Runtime.DataModel.DistanceUnit)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.searcharea.searcharea(v=AX.60)
ms:contentKeyID: 49846730
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SearchArea Constructor (Decimal, Decimal, Double, DistanceUnit)

Initializes a new instance of the [SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    latitude As Decimal, _
    longitude As Decimal, _
    radius As Double, _
    distanceUnit As DistanceUnit _
)
'Usage
Dim latitude As Decimal
Dim longitude As Decimal
Dim radius As Double
Dim distanceUnit As DistanceUnit

Dim instance As New SearchArea(latitude, _
    longitude, radius, distanceUnit)
```

``` csharp
public SearchArea(
    decimal latitude,
    decimal longitude,
    double radius,
    DistanceUnit distanceUnit
)
```

``` c++
public:
SearchArea(
    Decimal latitude, 
    Decimal longitude, 
    double radius, 
    DistanceUnit distanceUnit
)
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - radius  
    Type: [System.Double](https://technet.microsoft.com/en-us/library/643eft0t\(v=ax.60\))  

<!-- end list -->

  - distanceUnit  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DistanceUnit](distanceunit-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SearchArea Class](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[SearchArea Overload](searcharea-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

