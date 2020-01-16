---
title: OrgUnitAvailability Constructor (OrgUnitLocation, IEnumerable(ItemAvailability)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnitAvailability Constructor (OrgUnitLocation, IEnumerable(ItemAvailability))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitAvailability.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitavailability.orgunitavailability(v=AX.60)
ms:contentKeyID: 62206388
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# OrgUnitAvailability Constructor (OrgUnitLocation, IEnumerable(ItemAvailability))

Initializes a new instance of the [OrgUnitAvailability](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    orgUnitLocation As OrgUnitLocation, _
    itemAvailabilities As IEnumerable(Of ItemAvailability) _
)
'Usage
Dim orgUnitLocation As OrgUnitLocation
Dim itemAvailabilities As IEnumerable(Of ItemAvailability)

Dim instance As New OrgUnitAvailability(orgUnitLocation, _
    itemAvailabilities)
```

``` csharp
public OrgUnitAvailability(
    OrgUnitLocation orgUnitLocation,
    IEnumerable<ItemAvailability> itemAvailabilities
)
```

``` c++
public:
OrgUnitAvailability(
    OrgUnitLocation^ orgUnitLocation, 
    IEnumerable<ItemAvailability^>^ itemAvailabilities
)
```

#### Parameters

  - orgUnitLocation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemAvailabilities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrgUnitAvailability Class](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[OrgUnitAvailability Overload](orgunitavailability-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

