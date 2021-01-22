---
title: ChannelManager.GetCurrencies Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCurrencies Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetCurrencies(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getcurrencies(v=AX.60)
ms:contentKeyID: 65320135
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetCurrencies
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrencies Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrencies ( _
    settings As QueryResultSettings _
) As PagedResult(Of Currency)
'Usage
Dim instance As ChannelManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of Currency)

returnValue = instance.GetCurrencies(settings)
```

``` csharp
public PagedResult<Currency> GetCurrencies(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<Currency^>^ GetCurrencies(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[Currency](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

