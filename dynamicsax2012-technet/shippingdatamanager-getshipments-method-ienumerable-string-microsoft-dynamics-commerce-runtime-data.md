---
title: ShippingDataManager.GetShipments Method (IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShipments Method (IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetShipments(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getshipments(v=AX.60)
ms:contentKeyID: 62214411
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetShipments Method (IEnumerable(String))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets order shipment information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetShipments ( _
    shipmentIdCollection As IEnumerable(Of String) _
) As ReadOnlyCollection(Of Shipment)
'Usage
Dim instance As ShippingDataManager
Dim shipmentIdCollection As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of Shipment)

returnValue = instance.GetShipments(shipmentIdCollection)
```

``` csharp
public ReadOnlyCollection<Shipment> GetShipments(
    IEnumerable<string> shipmentIdCollection
)
```

``` c++
public:
ReadOnlyCollection<Shipment^>^ GetShipments(
    IEnumerable<String^>^ shipmentIdCollection
)
```

#### Parameters

  - shipmentIdCollection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of shipments.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetShipments Overload](shippingdatamanager-getshipments-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

