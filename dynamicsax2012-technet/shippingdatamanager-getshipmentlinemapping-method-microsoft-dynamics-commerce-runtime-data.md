---
title: ShippingDataManager.GetShipmentLineMapping Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShipmentLineMapping Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetShipmentLineMapping(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getshipmentlinemapping(v=AX.60)
ms:contentKeyID: 62205868
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetShipmentLineMapping
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentLineMapping Method

Gets the mapping between a sales line and all packing slips line that fulfill that sales line shipment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetShipmentLineMapping ( _
    salesOrderIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of ShipmentLineMapping)
'Usage
Dim instance As ShippingDataManager
Dim salesOrderIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of ShipmentLineMapping)

returnValue = instance.GetShipmentLineMapping(salesOrderIds)
```

``` csharp
public ReadOnlyCollection<ShipmentLineMapping> GetShipmentLineMapping(
    IEnumerable<string> salesOrderIds
)
```

``` c++
public:
ReadOnlyCollection<ShipmentLineMapping^>^ GetShipmentLineMapping(
    IEnumerable<String^>^ salesOrderIds
)
```

#### Parameters

  - salesOrderIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ShipmentLineMapping](shipmentlinemapping-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of mappings between sales lines and packing slip lines.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

