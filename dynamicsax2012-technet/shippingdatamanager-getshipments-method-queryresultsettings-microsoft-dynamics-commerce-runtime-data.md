---
title: ShippingDataManager.GetShipments Method (QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShipments Method (QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetShipments(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getshipments(v=AX.60)
ms:contentKeyID: 65321599
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetShipments Method (QueryResultSettings)

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This function may not be called until CRT implements support for change tracking of shipments.")> _
Public Function GetShipments ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Shipment)
'Usage
Dim instance As ShippingDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Shipment)

returnValue = instance.GetShipments(settings)
```

``` csharp
[ObsoleteAttribute("This function may not be called until CRT implements support for change tracking of shipments.")]
public ReadOnlyCollection<Shipment> GetShipments(
    QueryResultSettings settings
)
```

``` c++
[ObsoleteAttribute(L"This function may not be called until CRT implements support for change tracking of shipments.")]
public:
ReadOnlyCollection<Shipment^>^ GetShipments(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetShipments Overload](shippingdatamanager-getshipments-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

