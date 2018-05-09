---
title: ChannelManager.SearchStores Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SearchStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.SearchStores(Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchStoreCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.channelmanager.searchstores(v=AX.60)
ms:contentKeyID: 65322358
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.SearchStores
dev_langs:
- CSharp
- C++
- VB
---

# SearchStores Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SearchStores ( _
    searchStoreCriteria As SearchStoreCriteria, _
    settings As QueryResultSettings _
) As PagedResult(Of OrgUnit)
'Usage
Dim instance As ChannelManager
Dim searchStoreCriteria As SearchStoreCriteria
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of OrgUnit)

returnValue = instance.SearchStores(searchStoreCriteria, _
    settings)
```

``` csharp
public PagedResult<OrgUnit> SearchStores(
    SearchStoreCriteria searchStoreCriteria,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<OrgUnit^>^ SearchStores(
    SearchStoreCriteria^ searchStoreCriteria, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - searchStoreCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchStoreCriteria](searchstorecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

