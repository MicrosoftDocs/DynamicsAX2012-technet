---
title: ChannelDatabaseAccessor.GetChannelConfiguration Method (Int64) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelConfiguration Method (Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetChannelConfiguration(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getchannelconfiguration(v=AX.60)
ms:contentKeyID: 62206118
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelConfiguration Method (Int64)

Gets the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelConfiguration ( _
    channelId As Long _
) As ChannelConfiguration
'Usage
Dim instance As ChannelDatabaseAccessor
Dim channelId As Long
Dim returnValue As ChannelConfiguration

returnValue = instance.GetChannelConfiguration(channelId)
```

``` csharp
public ChannelConfiguration GetChannelConfiguration(
    long channelId
)
```

``` c++
public:
virtual ChannelConfiguration^ GetChannelConfiguration(
    long long channelId
) sealed
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The channel configuration.  

#### Implements

[IChannelDataManager.GetChannelConfiguration(Int64)](ichanneldatamanager-getchannelconfiguration-method-int64-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[GetChannelConfiguration Overload](channeldatabaseaccessor-getchannelconfiguration-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

