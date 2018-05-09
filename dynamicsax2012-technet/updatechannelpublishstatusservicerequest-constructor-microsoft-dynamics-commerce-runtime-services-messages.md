---
title: UpdateChannelPublishStatusServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UpdateChannelPublishStatusServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateChannelPublishStatusServiceRequest.#ctor(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.updatechannelpublishstatusservicerequest.updatechannelpublishstatusservicerequest(v=AX.60)
ms:contentKeyID: 65315610
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateChannelPublishStatusServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UpdateChannelPublishStatusServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    publishStatus As OnlineChannelPublishStatusType, _
    publishStatusMessage As String _
)
'Usage
Dim channelId As Long
Dim publishStatus As OnlineChannelPublishStatusType
Dim publishStatusMessage As String

Dim instance As New UpdateChannelPublishStatusServiceRequest(channelId, _
    publishStatus, publishStatusMessage)
```

``` csharp
public UpdateChannelPublishStatusServiceRequest(
    long channelId,
    OnlineChannelPublishStatusType publishStatus,
    string publishStatusMessage
)
```

``` c++
public:
UpdateChannelPublishStatusServiceRequest(
    long long channelId, 
    OnlineChannelPublishStatusType publishStatus, 
    String^ publishStatusMessage
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - publishStatus  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - publishStatusMessage  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[UpdateChannelPublishStatusServiceRequest Class](updatechannelpublishstatusservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

