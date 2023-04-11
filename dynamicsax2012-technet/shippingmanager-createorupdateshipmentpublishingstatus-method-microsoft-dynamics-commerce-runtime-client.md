---
title: ShippingManager.CreateOrUpdateShipmentPublishingStatus Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CreateOrUpdateShipmentPublishingStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.CreateOrUpdateShipmentPublishingStatus(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.shippingmanager.createorupdateshipmentpublishingstatus(v=AX.60)
ms:contentKeyID: 62213946
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.CreateOrUpdateShipmentPublishingStatus
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrUpdateShipmentPublishingStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates or updates shipment publishing status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub CreateOrUpdateShipmentPublishingStatus ( _
    shipmentStatuses As IEnumerable(Of ShipmentPublishingStatus) _
)
'Usage
Dim instance As ShippingManager
Dim shipmentStatuses As IEnumerable(Of ShipmentPublishingStatus)

instance.CreateOrUpdateShipmentPublishingStatus(shipmentStatuses)
```

``` csharp
public void CreateOrUpdateShipmentPublishingStatus(
    IEnumerable<ShipmentPublishingStatus> shipmentStatuses
)
```

``` c++
public:
void CreateOrUpdateShipmentPublishingStatus(
    IEnumerable<ShipmentPublishingStatus^>^ shipmentStatuses
)
```

#### Parameters

  - shipmentStatuses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ShipmentPublishingStatus](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ShippingManager Class](shippingmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

