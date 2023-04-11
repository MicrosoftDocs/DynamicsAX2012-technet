---
title: UpdateOnlineChannelPublishStatusRequest.PublishStatus Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PublishStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateOnlineChannelPublishStatusRequest.PublishStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.updateonlinechannelpublishstatusrequest.publishstatus(v=AX.60)
ms:contentKeyID: 49852863
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateOnlineChannelPublishStatusRequest.PublishStatus
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the publish status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PublishStatus As OnlineChannelPublishStatusType
    Get
    Set
'Usage
Dim instance As UpdateOnlineChannelPublishStatusRequest
Dim value As OnlineChannelPublishStatusType

value = instance.PublishStatus

instance.PublishStatus = value
```

``` csharp
[DataMemberAttribute]
public OnlineChannelPublishStatusType PublishStatus { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property OnlineChannelPublishStatusType PublishStatus {
    OnlineChannelPublishStatusType get ();
    void set (OnlineChannelPublishStatusType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The publish status.  

## See Also

#### Reference

[UpdateOnlineChannelPublishStatusRequest Class](updateonlinechannelpublishstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

