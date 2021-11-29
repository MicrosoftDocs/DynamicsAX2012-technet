---
title: UpdateChannelPublishingStatusRealtimeRequest.PublishStatusMessage Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PublishStatusMessage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPublishingStatusRealtimeRequest.PublishStatusMessage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.updatechannelpublishingstatusrealtimerequest.publishstatusmessage(v=AX.60)
ms:contentKeyID: 65316446
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPublishingStatusRealtimeRequest.PublishStatusMessage
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatusMessage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PublishStatusMessage As String
    Get
    Private Set
'Usage
Dim instance As UpdateChannelPublishingStatusRealtimeRequest
Dim value As String

value = instance.PublishStatusMessage
```

``` csharp
[DataMemberAttribute]
public string PublishStatusMessage { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PublishStatusMessage {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[UpdateChannelPublishingStatusRealtimeRequest Class](updatechannelpublishingstatusrealtimerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

