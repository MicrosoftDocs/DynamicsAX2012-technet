---
title: ChannelManager.GetChannelCashDeclarations Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelCashDeclarations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelCashDeclarations(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getchannelcashdeclarations(v=AX.60)
ms:contentKeyID: 65322124
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelCashDeclarations
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCashDeclarations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelCashDeclarations ( _
    settings As QueryResultSettings _
) As PagedResult(Of CashDeclaration)
'Usage
Dim instance As ChannelManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of CashDeclaration)

returnValue = instance.GetChannelCashDeclarations(settings)
```

``` csharp
public PagedResult<CashDeclaration> GetChannelCashDeclarations(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<CashDeclaration^>^ GetChannelCashDeclarations(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[CashDeclaration](cashdeclaration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

