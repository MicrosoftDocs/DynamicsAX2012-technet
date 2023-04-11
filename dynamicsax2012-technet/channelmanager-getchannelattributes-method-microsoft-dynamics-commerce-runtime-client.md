---
title: ChannelManager.GetChannelAttributes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelAttributes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelAttributes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getchannelattributes(v=AX.60)
ms:contentKeyID: 65322920
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelAttributes
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelAttributes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelAttributes ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ChannelAttribute)
'Usage
Dim instance As ChannelManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ChannelAttribute)

returnValue = instance.GetChannelAttributes(settings)
```

``` csharp
public ReadOnlyCollection<ChannelAttribute> GetChannelAttributes(
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<ChannelAttribute^>^ GetChannelAttributes(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChannelAttribute](channelattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

