---
title: IChannelDataManager.GetChannelConfiguration Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelConfiguration Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelConfiguration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getchannelconfiguration(v=AX.60)
ms:contentKeyID: 62209887
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelConfiguration Method

Gets the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetChannelConfiguration As ChannelConfiguration
'Usage
Dim instance As IChannelDataManager
Dim returnValue As ChannelConfiguration

returnValue = instance.GetChannelConfiguration()
```

``` csharp
ChannelConfiguration GetChannelConfiguration()
```

``` c++
ChannelConfiguration^ GetChannelConfiguration()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The channel configuration.  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[GetChannelConfiguration Overload](ichanneldatamanager-getchannelconfiguration-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

