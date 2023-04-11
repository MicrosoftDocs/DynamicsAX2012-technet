---
title: ChannelDatabaseAccessor.GetCurrentChannelLanguages Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCurrentChannelLanguages Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetCurrentChannelLanguages
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getcurrentchannellanguages(v=AX.60)
ms:contentKeyID: 62214527
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetCurrentChannelLanguages
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrentChannelLanguages Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the languages for the current channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrentChannelLanguages As ReadOnlyCollection(Of ChannelLanguage)
'Usage
Dim instance As ChannelDatabaseAccessor
Dim returnValue As ReadOnlyCollection(Of ChannelLanguage)

returnValue = instance.GetCurrentChannelLanguages()
```

``` csharp
public ReadOnlyCollection<ChannelLanguage> GetCurrentChannelLanguages()
```

``` c++
public:
ReadOnlyCollection<ChannelLanguage^>^ GetCurrentChannelLanguages()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChannelLanguage](channellanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of channel languages.  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

