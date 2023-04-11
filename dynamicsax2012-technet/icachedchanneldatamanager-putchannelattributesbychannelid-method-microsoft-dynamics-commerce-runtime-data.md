---
title: ICachedChannelDataManager.PutChannelAttributesByChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelAttributesByChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelAttributesByChannelId(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttribute})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchannelattributesbychannelid(v=AX.60)
ms:contentKeyID: 65320799
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelAttributesByChannelId
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelAttributesByChannelId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelAttributesByChannelId ( _
    channelId As Long, _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of ChannelAttribute) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of ChannelAttribute)

instance.PutChannelAttributesByChannelId(channelId, _
    settings, result)
```

``` csharp
void PutChannelAttributesByChannelId(
    long channelId,
    QueryResultSettings settings,
    ReadOnlyCollection<ChannelAttribute> result
)
```

``` c++
void PutChannelAttributesByChannelId(
    long long channelId, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<ChannelAttribute^>^ result
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChannelAttribute](channelattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

