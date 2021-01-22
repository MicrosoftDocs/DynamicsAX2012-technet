---
title: ChannelManager.GetChannelProfile Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelProfile Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelProfile(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getchannelprofile(v=AX.60)
ms:contentKeyID: 62214678
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelProfile
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelProfile Method

Gets channel's profile by the channel's ID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelProfile ( _
    channelId As Long _
) As ChannelProfile
'Usage
Dim instance As ChannelManager
Dim channelId As Long
Dim returnValue As ChannelProfile

returnValue = instance.GetChannelProfile(channelId)
```

``` csharp
public ChannelProfile GetChannelProfile(
    long channelId
)
```

``` c++
public:
ChannelProfile^ GetChannelProfile(
    long long channelId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The profile.  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

