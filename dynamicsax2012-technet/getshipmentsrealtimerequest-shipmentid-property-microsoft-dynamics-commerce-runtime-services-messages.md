---
title: GetShipmentsRealtimeRequest.ShipmentId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ShipmentId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsRealtimeRequest.ShipmentId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshipmentsrealtimerequest.shipmentid(v=AX.60)
ms:contentKeyID: 65316080
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsRealtimeRequest.ShipmentId
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentId As String
    Get
    Private Set
'Usage
Dim instance As GetShipmentsRealtimeRequest
Dim value As String

value = instance.ShipmentId
```

``` csharp
[DataMemberAttribute]
public string ShipmentId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ShipmentId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetShipmentsRealtimeRequest Class](getshipmentsrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

