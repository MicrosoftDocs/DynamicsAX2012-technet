---
title: ICachedChannelDataManager.PutChannelLanguagesByChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelLanguagesByChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelLanguagesByChannelId(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelLanguage})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchannellanguagesbychannelid(v=AX.60)
ms:contentKeyID: 65320264
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelLanguagesByChannelId
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelLanguagesByChannelId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelLanguagesByChannelId ( _
    channelId As Long, _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of ChannelLanguage) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of ChannelLanguage)

instance.PutChannelLanguagesByChannelId(channelId, _
    settings, result)
```

``` csharp
void PutChannelLanguagesByChannelId(
    long channelId,
    QueryResultSettings settings,
    ReadOnlyCollection<ChannelLanguage> result
)
```

``` c++
void PutChannelLanguagesByChannelId(
    long long channelId, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<ChannelLanguage^>^ result
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
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChannelLanguage](channellanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

