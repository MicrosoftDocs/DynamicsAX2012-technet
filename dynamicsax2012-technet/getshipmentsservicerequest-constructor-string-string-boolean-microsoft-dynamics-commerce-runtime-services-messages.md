---
title: GetShipmentsServiceRequest Constructor (String, String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetShipmentsServiceRequest Constructor (String, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsServiceRequest.#ctor(System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshipmentsservicerequest.getshipmentsservicerequest(v=AX.60)
ms:contentKeyID: 65319279
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetShipmentsServiceRequest Constructor (String, String, Boolean)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesId As String, _
    shipmentId As String, _
    getTrackingInfo As Boolean _
)
'Usage
Dim salesId As String
Dim shipmentId As String
Dim getTrackingInfo As Boolean

Dim instance As New GetShipmentsServiceRequest(salesId, _
    shipmentId, getTrackingInfo)
```

``` csharp
public GetShipmentsServiceRequest(
    string salesId,
    string shipmentId,
    bool getTrackingInfo
)
```

``` c++
public:
GetShipmentsServiceRequest(
    String^ salesId, 
    String^ shipmentId, 
    bool getTrackingInfo
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shipmentId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - getTrackingInfo  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetShipmentsServiceRequest Class](getshipmentsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetShipmentsServiceRequest Overload](getshipmentsservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

