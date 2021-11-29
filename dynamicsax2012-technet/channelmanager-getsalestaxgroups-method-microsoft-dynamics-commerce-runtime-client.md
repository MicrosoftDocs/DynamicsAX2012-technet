---
title: ChannelManager.GetSalesTaxGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetSalesTaxGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetSalesTaxGroups(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getsalestaxgroups(v=AX.60)
ms:contentKeyID: 65321544
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetSalesTaxGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesTaxGroups Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetSalesTaxGroups ( _
    settings As QueryResultSettings _
) As PagedResult(Of SalesTaxGroup)
'Usage
Dim instance As ChannelManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of SalesTaxGroup)

returnValue = instance.GetSalesTaxGroups(settings)
```

``` csharp
public PagedResult<SalesTaxGroup> GetSalesTaxGroups(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<SalesTaxGroup^>^ GetSalesTaxGroups(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[SalesTaxGroup](salestaxgroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

