---
title: ChannelManager.GetDeviceConfiguration Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetDeviceConfiguration Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetDeviceConfiguration(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getdeviceconfiguration(v=AX.60)
ms:contentKeyID: 65320330
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetDeviceConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# GetDeviceConfiguration Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetDeviceConfiguration ( _
    settings As QueryResultSettings _
) As DeviceConfiguration
'Usage
Dim instance As ChannelManager
Dim settings As QueryResultSettings
Dim returnValue As DeviceConfiguration

returnValue = instance.GetDeviceConfiguration(settings)
```

``` csharp
public DeviceConfiguration GetDeviceConfiguration(
    QueryResultSettings settings
)
```

``` c++
public:
DeviceConfiguration^ GetDeviceConfiguration(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

