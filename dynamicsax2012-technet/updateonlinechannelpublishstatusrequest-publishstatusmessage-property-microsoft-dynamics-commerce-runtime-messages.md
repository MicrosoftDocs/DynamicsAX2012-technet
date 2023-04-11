---
title: UpdateOnlineChannelPublishStatusRequest.PublishStatusMessage Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PublishStatusMessage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateOnlineChannelPublishStatusRequest.PublishStatusMessage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.updateonlinechannelpublishstatusrequest.publishstatusmessage(v=AX.60)
ms:contentKeyID: 49847021
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateOnlineChannelPublishStatusRequest.PublishStatusMessage
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatusMessage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the publish status message.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PublishStatusMessage As String
    Get
    Set
'Usage
Dim instance As UpdateOnlineChannelPublishStatusRequest
Dim value As String

value = instance.PublishStatusMessage

instance.PublishStatusMessage = value
```

``` csharp
[DataMemberAttribute]
public string PublishStatusMessage { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PublishStatusMessage {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The publish status message.  

## See Also

#### Reference

[UpdateOnlineChannelPublishStatusRequest Class](updateonlinechannelpublishstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

