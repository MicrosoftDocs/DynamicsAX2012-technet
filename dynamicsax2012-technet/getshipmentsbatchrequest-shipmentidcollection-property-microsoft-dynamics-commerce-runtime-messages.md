---
title: GetShipmentsBatchRequest.ShipmentIdCollection Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShipmentIdCollection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsBatchRequest.ShipmentIdCollection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getshipmentsbatchrequest.shipmentidcollection(v=AX.60)
ms:contentKeyID: 62212208
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsBatchRequest.ShipmentIdCollection
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentIdCollection Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a collection of shipment ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentIdCollection As IEnumerable(Of String)
    Get
    Set
'Usage
Dim instance As GetShipmentsBatchRequest
Dim value As IEnumerable(Of String)

value = instance.ShipmentIdCollection

instance.ShipmentIdCollection = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ShipmentIdCollection { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ShipmentIdCollection {
    IEnumerable<String^>^ get ();
    void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetShipmentsBatchRequest Class](getshipmentsbatchrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

