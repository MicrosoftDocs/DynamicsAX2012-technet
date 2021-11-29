---
title: ChannelManager.GetStoreByStoreNumber Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetStoreByStoreNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetStoreByStoreNumber(System.Collections.Generic.ICollection{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getstorebystorenumber(v=AX.60)
ms:contentKeyID: 65318224
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetStoreByStoreNumber
dev_langs:
- CSharp
- C++
- VB
---

# GetStoreByStoreNumber Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetStoreByStoreNumber ( _
    storeNumbers As ICollection(Of String), _
    settings As QueryResultSettings _
) As PagedResult(Of OrgUnit)
'Usage
Dim instance As ChannelManager
Dim storeNumbers As ICollection(Of String)
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of OrgUnit)

returnValue = instance.GetStoreByStoreNumber(storeNumbers, _
    settings)
```

``` csharp
public PagedResult<OrgUnit> GetStoreByStoreNumber(
    ICollection<string> storeNumbers,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<OrgUnit^>^ GetStoreByStoreNumber(
    ICollection<String^>^ storeNumbers, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - storeNumbers  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

