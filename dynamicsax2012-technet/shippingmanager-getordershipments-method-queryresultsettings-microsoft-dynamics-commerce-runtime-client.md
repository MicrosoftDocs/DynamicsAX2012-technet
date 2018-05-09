---
title: ShippingManager.GetOrderShipments Method (QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrderShipments Method (QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.GetOrderShipments(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.shippingmanager.getordershipments(v=AX.60)
ms:contentKeyID: 65323108
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOrderShipments Method (QueryResultSettings)

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This function may not be called until CRT implements support for change tracking of shipments.")> _
Public Function GetOrderShipments ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Shipment)
'Usage
Dim instance As ShippingManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Shipment)

returnValue = instance.GetOrderShipments(settings)
```

``` csharp
[ObsoleteAttribute("This function may not be called until CRT implements support for change tracking of shipments.")]
public ReadOnlyCollection<Shipment> GetOrderShipments(
    QueryResultSettings settings
)
```

``` c++
[ObsoleteAttribute(L"This function may not be called until CRT implements support for change tracking of shipments.")]
public:
ReadOnlyCollection<Shipment^>^ GetOrderShipments(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ShippingManager Class](shippingmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetOrderShipments Overload](shippingmanager-getordershipments-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

