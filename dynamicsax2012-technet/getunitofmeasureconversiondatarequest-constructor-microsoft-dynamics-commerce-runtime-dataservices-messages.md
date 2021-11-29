---
title: GetUnitOfMeasureConversionDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetUnitOfMeasureConversionDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getunitofmeasureconversiondatarequest.getunitofmeasureconversiondatarequest(v=AX.60)
ms:contentKeyID: 65321492
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetUnitOfMeasureConversionDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetUnitOfMeasureConversionDataRequest](getunitofmeasureconversiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemUnitConversions As IEnumerable(Of ItemUnitConversion), _
    settings As QueryResultSettings _
)
'Usage
Dim itemUnitConversions As IEnumerable(Of ItemUnitConversion)
Dim settings As QueryResultSettings

Dim instance As New GetUnitOfMeasureConversionDataRequest(itemUnitConversions, _
    settings)
```

``` csharp
public GetUnitOfMeasureConversionDataRequest(
    IEnumerable<ItemUnitConversion> itemUnitConversions,
    QueryResultSettings settings
)
```

``` c++
public:
GetUnitOfMeasureConversionDataRequest(
    IEnumerable<ItemUnitConversion^>^ itemUnitConversions, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - itemUnitConversions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnitConversion](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetUnitOfMeasureConversionDataRequest Class](getunitofmeasureconversiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

