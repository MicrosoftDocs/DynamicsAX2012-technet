---
title: UpdateChannelPublishingStatusRealtimeRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: UpdateChannelPublishingStatusRealtimeRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPublishingStatusRealtimeRequest.#ctor(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.updatechannelpublishingstatusrealtimerequest.updatechannelpublishingstatusrealtimerequest(v=AX.60)
ms:contentKeyID: 65320460
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPublishingStatusRealtimeRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UpdateChannelPublishingStatusRealtimeRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    publishingStatus As OnlineChannelPublishStatusType, _
    publishingStatusMessage As String _
)
'Usage
Dim channelId As Long
Dim publishingStatus As OnlineChannelPublishStatusType
Dim publishingStatusMessage As String

Dim instance As New UpdateChannelPublishingStatusRealtimeRequest(channelId, _
    publishingStatus, publishingStatusMessage)
```

``` csharp
public UpdateChannelPublishingStatusRealtimeRequest(
    long channelId,
    OnlineChannelPublishStatusType publishingStatus,
    string publishingStatusMessage
)
```

``` c++
public:
UpdateChannelPublishingStatusRealtimeRequest(
    long long channelId, 
    OnlineChannelPublishStatusType publishingStatus, 
    String^ publishingStatusMessage
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - publishingStatus  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - publishingStatusMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[UpdateChannelPublishingStatusRealtimeRequest Class](updatechannelpublishingstatusrealtimerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

