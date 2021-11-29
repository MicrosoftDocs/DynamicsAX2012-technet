---
title: GetShipmentsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetShipmentsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshipmentsserviceresponse.getshipmentsserviceresponse(v=AX.60)
ms:contentKeyID: 49834853
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentsServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetShipmentsServiceResponse](getshipmentsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shipments As IEnumerable(Of Shipment) _
)
'Usage
Dim shipments As IEnumerable(Of Shipment)

Dim instance As New GetShipmentsServiceResponse(shipments)
```

``` csharp
public GetShipmentsServiceResponse(
    IEnumerable<Shipment> shipments
)
```

``` c++
public:
GetShipmentsServiceResponse(
    IEnumerable<Shipment^>^ shipments
)
```

#### Parameters

  - shipments  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetShipmentsServiceResponse Class](getshipmentsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

