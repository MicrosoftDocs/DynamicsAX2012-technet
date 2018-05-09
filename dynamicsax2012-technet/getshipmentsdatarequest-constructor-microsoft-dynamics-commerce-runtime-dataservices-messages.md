---
title: GetShipmentsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetShipmentsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshipmentsdatarequest.getshipmentsdatarequest(v=AX.60)
ms:contentKeyID: 65318282
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentsDataRequest Constructor

Initializes a new instance of the [GetShipmentsDataRequest](getshipmentsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shipmentIds As IEnumerable(Of String) _
)
'Usage
Dim shipmentIds As IEnumerable(Of String)

Dim instance As New GetShipmentsDataRequest(shipmentIds)
```

``` csharp
public GetShipmentsDataRequest(
    IEnumerable<string> shipmentIds
)
```

``` c++
public:
GetShipmentsDataRequest(
    IEnumerable<String^>^ shipmentIds
)
```

#### Parameters

  - shipmentIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetShipmentsDataRequest Class](getshipmentsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

