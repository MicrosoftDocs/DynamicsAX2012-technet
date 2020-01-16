---
title: GetUnitOfMeasureConversionDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetUnitOfMeasureConversionDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getunitofmeasureconversiondataresponse.getunitofmeasureconversiondataresponse(v=AX.60)
ms:contentKeyID: 65320637
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetUnitOfMeasureConversionDataResponse Constructor

Initializes a new instance of the [GetUnitOfMeasureConversionDataResponse](getunitofmeasureconversiondataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    unitConversions As ReadOnlyCollection(Of UnitOfMeasureConversion) _
)
'Usage
Dim unitConversions As ReadOnlyCollection(Of UnitOfMeasureConversion)

Dim instance As New GetUnitOfMeasureConversionDataResponse(unitConversions)
```

``` csharp
public GetUnitOfMeasureConversionDataResponse(
    ReadOnlyCollection<UnitOfMeasureConversion> unitConversions
)
```

``` c++
public:
GetUnitOfMeasureConversionDataResponse(
    ReadOnlyCollection<UnitOfMeasureConversion^>^ unitConversions
)
```

#### Parameters

  - unitConversions  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetUnitOfMeasureConversionDataResponse Class](getunitofmeasureconversiondataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

