---
title: ChannelManager.GetHardwareProfile Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetHardwareProfile Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetHardwareProfile(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.gethardwareprofile(v=AX.60)
ms:contentKeyID: 62208897
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetHardwareProfile
dev_langs:
- CSharp
- C++
- VB
---

# GetHardwareProfile Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get hardware profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetHardwareProfile ( _
    profileId As String _
) As HardwareProfile
'Usage
Dim instance As ChannelManager
Dim profileId As String
Dim returnValue As HardwareProfile

returnValue = instance.GetHardwareProfile(profileId)
```

``` csharp
public HardwareProfile GetHardwareProfile(
    string profileId
)
```

``` c++
public:
HardwareProfile^ GetHardwareProfile(
    String^ profileId
)
```

#### Parameters

  - profileId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Hardware profile.  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

