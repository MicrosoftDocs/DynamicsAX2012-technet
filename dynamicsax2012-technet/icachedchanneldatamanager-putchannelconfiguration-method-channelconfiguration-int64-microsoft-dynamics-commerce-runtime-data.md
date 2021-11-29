---
title: ICachedChannelDataManager.PutChannelConfiguration Method (ChannelConfiguration, Int64) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelConfiguration Method (ChannelConfiguration, Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelConfiguration(Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchannelconfiguration(v=AX.60)
ms:contentKeyID: 62203252
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutChannelConfiguration Method (ChannelConfiguration, Int64)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Caches the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelConfiguration ( _
    result As ChannelConfiguration, _
    channelId As Long _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim result As ChannelConfiguration
Dim channelId As Long

instance.PutChannelConfiguration(result, _
    channelId)
```

``` csharp
void PutChannelConfiguration(
    ChannelConfiguration result,
    long channelId
)
```

``` c++
void PutChannelConfiguration(
    ChannelConfiguration^ result, 
    long long channelId
)
```

#### Parameters

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[PutChannelConfiguration Overload](icachedchanneldatamanager-putchannelconfiguration-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

