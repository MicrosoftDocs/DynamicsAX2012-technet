---
title: ShippingManager.GetOrderShipmentLineMapping Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrderShipmentLineMapping Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.GetOrderShipmentLineMapping(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.shippingmanager.getordershipmentlinemapping(v=AX.60)
ms:contentKeyID: 62207583
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.GetOrderShipmentLineMapping
dev_langs:
- CSharp
- C++
- VB
---

# GetOrderShipmentLineMapping Method

Gets order shipment line mapping information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrderShipmentLineMapping ( _
    salesIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of ShipmentLineMapping)
'Usage
Dim instance As ShippingManager
Dim salesIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of ShipmentLineMapping)

returnValue = instance.GetOrderShipmentLineMapping(salesIds)
```

``` csharp
public ReadOnlyCollection<ShipmentLineMapping> GetOrderShipmentLineMapping(
    IEnumerable<string> salesIds
)
```

``` c++
public:
ReadOnlyCollection<ShipmentLineMapping^>^ GetOrderShipmentLineMapping(
    IEnumerable<String^>^ salesIds
)
```

#### Parameters

  - salesIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ShipmentLineMapping](shipmentlinemapping-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of shipments.  

## See Also

#### Reference

[ShippingManager Class](shippingmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

