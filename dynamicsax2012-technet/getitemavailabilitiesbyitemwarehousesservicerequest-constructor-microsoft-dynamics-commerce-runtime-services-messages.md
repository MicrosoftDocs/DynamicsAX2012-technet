---
title: GetItemAvailabilitiesByItemWarehousesServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetItemAvailabilitiesByItemWarehousesServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemWarehousesServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemWarehouse})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemwarehousesservicerequest.getitemavailabilitiesbyitemwarehousesservicerequest(v=AX.60)
ms:contentKeyID: 65323203
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemWarehousesServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesByItemWarehousesServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    itemWarehouses As IEnumerable(Of ItemWarehouse) _
)
'Usage
Dim settings As QueryResultSettings
Dim itemWarehouses As IEnumerable(Of ItemWarehouse)

Dim instance As New GetItemAvailabilitiesByItemWarehousesServiceRequest(settings, _
    itemWarehouses)
```

``` csharp
public GetItemAvailabilitiesByItemWarehousesServiceRequest(
    QueryResultSettings settings,
    IEnumerable<ItemWarehouse> itemWarehouses
)
```

``` c++
public:
GetItemAvailabilitiesByItemWarehousesServiceRequest(
    QueryResultSettings^ settings, 
    IEnumerable<ItemWarehouse^>^ itemWarehouses
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemWarehouses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemWarehouse](itemwarehouse-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetItemAvailabilitiesByItemWarehousesServiceRequest Class](getitemavailabilitiesbyitemwarehousesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

