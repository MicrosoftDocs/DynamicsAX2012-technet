---
title: ChannelDatabaseAccessor.GetChannelConfiguration Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelConfiguration Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetChannelConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getchannelconfiguration(v=AX.60)
ms:contentKeyID: 62215169
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelConfiguration Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelConfiguration As ChannelConfiguration
'Usage
Dim instance As ChannelDatabaseAccessor
Dim returnValue As ChannelConfiguration

returnValue = instance.GetChannelConfiguration()
```

``` csharp
public ChannelConfiguration GetChannelConfiguration()
```

``` c++
public:
virtual ChannelConfiguration^ GetChannelConfiguration() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The channel configuration.  

#### Implements

[IChannelDataManager.GetChannelConfiguration()](ichanneldatamanager-getchannelconfiguration-method-microsoft-dynamics-commerce-runtime-data_1.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[GetChannelConfiguration Overload](channeldatabaseaccessor-getchannelconfiguration-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

