---
title: UpdateChannelPublishingStatusRealtimeRequest.PublishStatus Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PublishStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPublishingStatusRealtimeRequest.PublishStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.updatechannelpublishingstatusrealtimerequest.publishstatus(v=AX.60)
ms:contentKeyID: 65319884
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPublishingStatusRealtimeRequest.PublishStatus
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatus Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PublishStatus As OnlineChannelPublishStatusType
    Get
    Private Set
'Usage
Dim instance As UpdateChannelPublishingStatusRealtimeRequest
Dim value As OnlineChannelPublishStatusType

value = instance.PublishStatus
```

``` csharp
[DataMemberAttribute]
public OnlineChannelPublishStatusType PublishStatus { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property OnlineChannelPublishStatusType PublishStatus {
    OnlineChannelPublishStatusType get ();
    private: void set (OnlineChannelPublishStatusType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[UpdateChannelPublishingStatusRealtimeRequest Class](updatechannelpublishingstatusrealtimerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

