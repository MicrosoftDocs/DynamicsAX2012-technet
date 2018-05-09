---
title: CreateOrUpdateShipmentStatusDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CreateOrUpdateShipmentStatusDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateShipmentStatusDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.createorupdateshipmentstatusdatarequest.createorupdateshipmentstatusdatarequest(v=AX.60)
ms:contentKeyID: 65316704
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateShipmentStatusDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrUpdateShipmentStatusDataRequest Constructor

Initializes a new instance of the [CreateOrUpdateShipmentStatusDataRequest](createorupdateshipmentstatusdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shipmentPublishingStatuses As IEnumerable(Of ShipmentPublishingStatus) _
)
'Usage
Dim shipmentPublishingStatuses As IEnumerable(Of ShipmentPublishingStatus)

Dim instance As New CreateOrUpdateShipmentStatusDataRequest(shipmentPublishingStatuses)
```

``` csharp
public CreateOrUpdateShipmentStatusDataRequest(
    IEnumerable<ShipmentPublishingStatus> shipmentPublishingStatuses
)
```

``` c++
public:
CreateOrUpdateShipmentStatusDataRequest(
    IEnumerable<ShipmentPublishingStatus^>^ shipmentPublishingStatuses
)
```

#### Parameters

  - shipmentPublishingStatuses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ShipmentPublishingStatus](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CreateOrUpdateShipmentStatusDataRequest Class](createorupdateshipmentstatusdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

