---
title: GetShipmentsDataRequest.ShipmentIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ShipmentIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentsDataRequest.ShipmentIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshipmentsdatarequest.shipmentids(v=AX.60)
ms:contentKeyID: 65320582
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentsDataRequest.ShipmentIds
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentIds Property

Gets the shipment identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetShipmentsDataRequest
Dim value As IEnumerable(Of String)

value = instance.ShipmentIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ShipmentIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ShipmentIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
The shipments identifiers.  

## See Also

#### Reference

[GetShipmentsDataRequest Class](getshipmentsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

