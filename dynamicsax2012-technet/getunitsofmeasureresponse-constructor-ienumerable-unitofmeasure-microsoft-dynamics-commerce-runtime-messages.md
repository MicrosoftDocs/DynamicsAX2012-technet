---
title: GetUnitsOfMeasureResponse Constructor (IEnumerable(UnitOfMeasure)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetUnitsOfMeasureResponse Constructor (IEnumerable(UnitOfMeasure))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasure})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getunitsofmeasureresponse.getunitsofmeasureresponse(v=AX.60)
ms:contentKeyID: 62208619
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetUnitsOfMeasureResponse Constructor (IEnumerable(UnitOfMeasure))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetUnitsOfMeasureResponse](getunitsofmeasureresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    unitsOfMeasure As IEnumerable(Of UnitOfMeasure) _
)
'Usage
Dim unitsOfMeasure As IEnumerable(Of UnitOfMeasure)

Dim instance As New GetUnitsOfMeasureResponse(unitsOfMeasure)
```

``` csharp
public GetUnitsOfMeasureResponse(
    IEnumerable<UnitOfMeasure> unitsOfMeasure
)
```

``` c++
public:
GetUnitsOfMeasureResponse(
    IEnumerable<UnitOfMeasure^>^ unitsOfMeasure
)
```

#### Parameters

  - unitsOfMeasure  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[UnitOfMeasure](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetUnitsOfMeasureResponse Class](getunitsofmeasureresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetUnitsOfMeasureResponse Overload](getunitsofmeasureresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

