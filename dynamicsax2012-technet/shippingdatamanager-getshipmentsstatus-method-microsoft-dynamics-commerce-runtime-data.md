---
title: ShippingDataManager.GetShipmentsStatus Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShipmentsStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetShipmentsStatus(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getshipmentsstatus(v=AX.60)
ms:contentKeyID: 65316941
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetShipmentsStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentsStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This function may not be called until CRT implements support for change tracking of shipments.")> _
Public Function GetShipmentsStatus ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ShipmentPublishingStatus)
'Usage
Dim instance As ShippingDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ShipmentPublishingStatus)

returnValue = instance.GetShipmentsStatus(settings)
```

``` csharp
[ObsoleteAttribute("This function may not be called until CRT implements support for change tracking of shipments.")]
public ReadOnlyCollection<ShipmentPublishingStatus> GetShipmentsStatus(
    QueryResultSettings settings
)
```

``` c++
[ObsoleteAttribute(L"This function may not be called until CRT implements support for change tracking of shipments.")]
public:
ReadOnlyCollection<ShipmentPublishingStatus^>^ GetShipmentsStatus(
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

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

