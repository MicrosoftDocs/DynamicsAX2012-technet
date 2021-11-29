---
title: GetWarehouseDetailsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetWarehouseDetailsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseDetailsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getwarehousedetailsdatarequest.getwarehousedetailsdatarequest(v=AX.60)
ms:contentKeyID: 65318550
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseDetailsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetWarehouseDetailsDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetWarehouseDetailsDataRequest](getwarehousedetailsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    warehouseIds As IEnumerable(Of String), _
    settings As QueryResultSettings _
)
'Usage
Dim warehouseIds As IEnumerable(Of String)
Dim settings As QueryResultSettings

Dim instance As New GetWarehouseDetailsDataRequest(warehouseIds, _
    settings)
```

``` csharp
public GetWarehouseDetailsDataRequest(
    IEnumerable<string> warehouseIds,
    QueryResultSettings settings
)
```

``` c++
public:
GetWarehouseDetailsDataRequest(
    IEnumerable<String^>^ warehouseIds, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - warehouseIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetWarehouseDetailsDataRequest Class](getwarehousedetailsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

