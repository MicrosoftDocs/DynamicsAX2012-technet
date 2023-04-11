---
title: GetItemDimensionsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetItemDimensionsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDimensionsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemdimensionsdatarequest.getitemdimensionsdatarequest(v=AX.60)
ms:contentKeyID: 65318176
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDimensionsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemDimensionsDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetItemDimensionsDataRequest](getitemdimensionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemIds As IEnumerable(Of String), _
    settings As QueryResultSettings _
)
'Usage
Dim itemIds As IEnumerable(Of String)
Dim settings As QueryResultSettings

Dim instance As New GetItemDimensionsDataRequest(itemIds, _
    settings)
```

``` csharp
public GetItemDimensionsDataRequest(
    IEnumerable<string> itemIds,
    QueryResultSettings settings
)
```

``` c++
public:
GetItemDimensionsDataRequest(
    IEnumerable<String^>^ itemIds, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetItemDimensionsDataRequest Class](getitemdimensionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

