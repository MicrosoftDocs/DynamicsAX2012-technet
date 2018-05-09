---
title: GetShipmentPublishingStatusResponse Constructor (IEnumerable(ShipmentPublishingStatus)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetShipmentPublishingStatusResponse Constructor (IEnumerable(ShipmentPublishingStatus))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentPublishingStatusResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getshipmentpublishingstatusresponse.getshipmentpublishingstatusresponse(v=AX.60)
ms:contentKeyID: 62212060
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetShipmentPublishingStatusResponse Constructor (IEnumerable(ShipmentPublishingStatus))

Initializes a new instance of the [GetShipmentPublishingStatusResponse](getshipmentpublishingstatusresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shipmentPublishingStatusCollection As IEnumerable(Of ShipmentPublishingStatus) _
)
'Usage
Dim shipmentPublishingStatusCollection As IEnumerable(Of ShipmentPublishingStatus)

Dim instance As New GetShipmentPublishingStatusResponse(shipmentPublishingStatusCollection)
```

``` csharp
public GetShipmentPublishingStatusResponse(
    IEnumerable<ShipmentPublishingStatus> shipmentPublishingStatusCollection
)
```

``` c++
public:
GetShipmentPublishingStatusResponse(
    IEnumerable<ShipmentPublishingStatus^>^ shipmentPublishingStatusCollection
)
```

#### Parameters

  - shipmentPublishingStatusCollection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ShipmentPublishingStatus](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetShipmentPublishingStatusResponse Class](getshipmentpublishingstatusresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetShipmentPublishingStatusResponse Overload](getshipmentpublishingstatusresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

