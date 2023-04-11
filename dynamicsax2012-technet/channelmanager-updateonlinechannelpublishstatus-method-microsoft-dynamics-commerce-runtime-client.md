---
title: ChannelManager.UpdateOnlineChannelPublishStatus Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateOnlineChannelPublishStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.UpdateOnlineChannelPublishStatus(Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.updateonlinechannelpublishstatus(v=AX.60)
ms:contentKeyID: 49854850
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.UpdateOnlineChannelPublishStatus
dev_langs:
- CSharp
- C++
- VB
---

# UpdateOnlineChannelPublishStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Update the publishing status of the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateOnlineChannelPublishStatus ( _
    publishStatus As OnlineChannelPublishStatusType, _
    publishStatusMessage As String _
)
'Usage
Dim instance As ChannelManager
Dim publishStatus As OnlineChannelPublishStatusType
Dim publishStatusMessage As String

instance.UpdateOnlineChannelPublishStatus(publishStatus, _
    publishStatusMessage)
```

``` csharp
public void UpdateOnlineChannelPublishStatus(
    OnlineChannelPublishStatusType publishStatus,
    string publishStatusMessage
)
```

``` c++
public:
void UpdateOnlineChannelPublishStatus(
    OnlineChannelPublishStatusType publishStatus, 
    String^ publishStatusMessage
)
```

#### Parameters

  - publishStatus  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - publishStatusMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

