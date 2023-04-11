---
title: GetShipmentsResponse Constructor (IEnumerable(Shipment)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetShipmentsResponse Constructor (IEnumerable(Shipment))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getshipmentsresponse.getshipmentsresponse(v=AX.60)
ms:contentKeyID: 49846381
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetShipmentsResponse Constructor (IEnumerable(Shipment))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetShipmentsResponse](getshipmentsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shipments As IEnumerable(Of Shipment) _
)
'Usage
Dim shipments As IEnumerable(Of Shipment)

Dim instance As New GetShipmentsResponse(shipments)
```

``` csharp
public GetShipmentsResponse(
    IEnumerable<Shipment> shipments
)
```

``` c++
public:
GetShipmentsResponse(
    IEnumerable<Shipment^>^ shipments
)
```

#### Parameters

  - shipments  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetShipmentsResponse Class](getshipmentsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetShipmentsResponse Overload](getshipmentsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

