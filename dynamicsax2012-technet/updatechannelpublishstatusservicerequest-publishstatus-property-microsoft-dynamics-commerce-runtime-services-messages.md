---
title: UpdateChannelPublishStatusServiceRequest.PublishStatus Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PublishStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateChannelPublishStatusServiceRequest.PublishStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.updatechannelpublishstatusservicerequest.publishstatus(v=AX.60)
ms:contentKeyID: 65321754
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateChannelPublishStatusServiceRequest.PublishStatus
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatus Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PublishStatus As OnlineChannelPublishStatusType
    Get
    Private Set
'Usage
Dim instance As UpdateChannelPublishStatusServiceRequest
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

[UpdateChannelPublishStatusServiceRequest Class](updatechannelpublishstatusservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

