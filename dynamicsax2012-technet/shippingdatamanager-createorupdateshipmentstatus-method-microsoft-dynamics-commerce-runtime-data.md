---
title: ShippingDataManager.CreateOrUpdateShipmentStatus Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CreateOrUpdateShipmentStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.CreateOrUpdateShipmentStatus(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.createorupdateshipmentstatus(v=AX.60)
ms:contentKeyID: 62209234
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.CreateOrUpdateShipmentStatus
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrUpdateShipmentStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates or updates shipments status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub CreateOrUpdateShipmentStatus ( _
    shipmentsStatus As IEnumerable(Of ShipmentPublishingStatus) _
)
'Usage
Dim instance As ShippingDataManager
Dim shipmentsStatus As IEnumerable(Of ShipmentPublishingStatus)

instance.CreateOrUpdateShipmentStatus(shipmentsStatus)
```

``` csharp
public void CreateOrUpdateShipmentStatus(
    IEnumerable<ShipmentPublishingStatus> shipmentsStatus
)
```

``` c++
public:
void CreateOrUpdateShipmentStatus(
    IEnumerable<ShipmentPublishingStatus^>^ shipmentsStatus
)
```

#### Parameters

  - shipmentsStatus  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ShipmentPublishingStatus](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

