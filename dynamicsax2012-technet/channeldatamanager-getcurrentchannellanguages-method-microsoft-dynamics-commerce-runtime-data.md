---
title: ChannelDataManager.GetCurrentChannelLanguages Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCurrentChannelLanguages Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetCurrentChannelLanguages
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getcurrentchannellanguages(v=AX.60)
ms:contentKeyID: 49850263
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetCurrentChannelLanguages
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrentChannelLanguages Method

Gets the languages for the current channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrentChannelLanguages As ReadOnlyCollection(Of ChannelLanguage)
'Usage
Dim instance As ChannelDataManager
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

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

