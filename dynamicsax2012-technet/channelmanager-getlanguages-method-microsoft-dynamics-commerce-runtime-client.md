---
title: ChannelManager.GetLanguages Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLanguages Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetLanguages(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getlanguages(v=AX.60)
ms:contentKeyID: 65322432
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetLanguages
dev_langs:
- CSharp
- C++
- VB
---

# GetLanguages Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLanguages ( _
    settings As QueryResultSettings _
) As PagedResult(Of SupportedLanguage)
'Usage
Dim instance As ChannelManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of SupportedLanguage)

returnValue = instance.GetLanguages(settings)
```

``` csharp
public PagedResult<SupportedLanguage> GetLanguages(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<SupportedLanguage^>^ GetLanguages(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[SupportedLanguage](supportedlanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

