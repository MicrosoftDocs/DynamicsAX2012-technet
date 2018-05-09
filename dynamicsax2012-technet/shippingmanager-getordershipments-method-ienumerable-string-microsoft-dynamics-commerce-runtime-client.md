---
title: ShippingManager.GetOrderShipments Method (IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrderShipments Method (IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.GetOrderShipments(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.shippingmanager.getordershipments(v=AX.60)
ms:contentKeyID: 62208492
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOrderShipments Method (IEnumerable(String))

Gets order shipment information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrderShipments ( _
    shipmentIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of Shipment)
'Usage
Dim instance As ShippingManager
Dim shipmentIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of Shipment)

returnValue = instance.GetOrderShipments(shipmentIds)
```

``` csharp
public ReadOnlyCollection<Shipment> GetOrderShipments(
    IEnumerable<string> shipmentIds
)
```

``` c++
public:
ReadOnlyCollection<Shipment^>^ GetOrderShipments(
    IEnumerable<String^>^ shipmentIds
)
```

#### Parameters

  - shipmentIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of shipments.  

## See Also

#### Reference

[ShippingManager Class](shippingmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetOrderShipments Overload](shippingmanager-getordershipments-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

