---
title: IChannelDataManager.GetChannelConfiguration Method (Int64) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelConfiguration Method (Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelConfiguration(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getchannelconfiguration(v=AX.60)
ms:contentKeyID: 62209993
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelConfiguration Method (Int64)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetChannelConfiguration ( _
    channelId As Long _
) As ChannelConfiguration
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim returnValue As ChannelConfiguration

returnValue = instance.GetChannelConfiguration(channelId)
```

``` csharp
ChannelConfiguration GetChannelConfiguration(
    long channelId
)
```

``` c++
ChannelConfiguration^ GetChannelConfiguration(
    long long channelId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The channel configuration.  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[GetChannelConfiguration Overload](ichanneldatamanager-getchannelconfiguration-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

