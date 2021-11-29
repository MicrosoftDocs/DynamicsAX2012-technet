---
title: GetShipmentsRequest.ShipmentId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShipmentId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsRequest.ShipmentId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getshipmentsrequest.shipmentid(v=AX.60)
ms:contentKeyID: 49825762
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsRequest.ShipmentId
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the packing slip/shipment identifier of the order to query for shipment information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentId As String
    Get
    Set
'Usage
Dim instance As GetShipmentsRequest
Dim value As String

value = instance.ShipmentId

instance.ShipmentId = value
```

``` csharp
[DataMemberAttribute]
public string ShipmentId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ShipmentId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetShipmentsRequest Class](getshipmentsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

