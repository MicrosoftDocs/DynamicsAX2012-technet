---
title: GetShipmentLineMappingResponse Constructor (ReadOnlyCollection(ShipmentLineMapping)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetShipmentLineMappingResponse Constructor (ReadOnlyCollection(ShipmentLineMapping))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentLineMappingResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getshipmentlinemappingresponse.getshipmentlinemappingresponse(v=AX.60)
ms:contentKeyID: 62211442
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetShipmentLineMappingResponse Constructor (ReadOnlyCollection(ShipmentLineMapping))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetShipmentLineMappingResponse](getshipmentlinemappingresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shipmentLineMappingIds As ReadOnlyCollection(Of ShipmentLineMapping) _
)
'Usage
Dim shipmentLineMappingIds As ReadOnlyCollection(Of ShipmentLineMapping)

Dim instance As New GetShipmentLineMappingResponse(shipmentLineMappingIds)
```

``` csharp
public GetShipmentLineMappingResponse(
    ReadOnlyCollection<ShipmentLineMapping> shipmentLineMappingIds
)
```

``` c++
public:
GetShipmentLineMappingResponse(
    ReadOnlyCollection<ShipmentLineMapping^>^ shipmentLineMappingIds
)
```

#### Parameters

  - shipmentLineMappingIds  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ShipmentLineMapping](shipmentlinemapping-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetShipmentLineMappingResponse Class](getshipmentlinemappingresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetShipmentLineMappingResponse Overload](getshipmentlinemappingresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

