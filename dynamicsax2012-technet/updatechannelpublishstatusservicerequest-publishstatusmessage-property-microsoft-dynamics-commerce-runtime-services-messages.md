---
title: UpdateChannelPublishStatusServiceRequest.PublishStatusMessage Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PublishStatusMessage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateChannelPublishStatusServiceRequest.PublishStatusMessage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.updatechannelpublishstatusservicerequest.publishstatusmessage(v=AX.60)
ms:contentKeyID: 65315528
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateChannelPublishStatusServiceRequest.PublishStatusMessage
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatusMessage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PublishStatusMessage As String
    Get
    Private Set
'Usage
Dim instance As UpdateChannelPublishStatusServiceRequest
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

[UpdateChannelPublishStatusServiceRequest Class](updatechannelpublishstatusservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

