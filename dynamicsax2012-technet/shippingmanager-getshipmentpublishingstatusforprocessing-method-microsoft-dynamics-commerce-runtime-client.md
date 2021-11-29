---
title: ShippingManager.GetShipmentPublishingStatusForProcessing Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetShipmentPublishingStatusForProcessing Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.GetShipmentPublishingStatusForProcessing(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.shippingmanager.getshipmentpublishingstatusforprocessing(v=AX.60)
ms:contentKeyID: 65319910
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.GetShipmentPublishingStatusForProcessing
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentPublishingStatusForProcessing Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This function may not be called until CRT implements support for change tracking of shipments.")> _
Public Function GetShipmentPublishingStatusForProcessing ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ShipmentPublishingStatus)
'Usage
Dim instance As ShippingManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ShipmentPublishingStatus)

returnValue = instance.GetShipmentPublishingStatusForProcessing(settings)
```

``` csharp
[ObsoleteAttribute("This function may not be called until CRT implements support for change tracking of shipments.")]
public ReadOnlyCollection<ShipmentPublishingStatus> GetShipmentPublishingStatusForProcessing(
    QueryResultSettings settings
)
```

``` c++
[ObsoleteAttribute(L"This function may not be called until CRT implements support for change tracking of shipments.")]
public:
ReadOnlyCollection<ShipmentPublishingStatus^>^ GetShipmentPublishingStatusForProcessing(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ShipmentPublishingStatus](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ShippingManager Class](shippingmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

