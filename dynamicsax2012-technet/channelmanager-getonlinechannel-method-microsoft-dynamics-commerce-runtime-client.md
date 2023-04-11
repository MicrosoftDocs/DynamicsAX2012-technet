---
title: ChannelManager.GetOnlineChannel Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOnlineChannel Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetOnlineChannel(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getonlinechannel(v=AX.60)
ms:contentKeyID: 49852809
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetOnlineChannel
dev_langs:
- CSharp
- C++
- VB
---

# GetOnlineChannel Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets an online channel by the unique channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOnlineChannel ( _
    channelId As Long _
) As OnlineChannel
'Usage
Dim instance As ChannelManager
Dim channelId As Long
Dim returnValue As OnlineChannel

returnValue = instance.GetOnlineChannel(channelId)
```

``` csharp
public OnlineChannel GetOnlineChannel(
    long channelId
)
```

``` c++
public:
OnlineChannel^ GetOnlineChannel(
    long long channelId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel](onlinechannel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The online channel.  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

