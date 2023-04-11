---
title: ChannelManager.GetCardTypes Method (QueryResultSettings, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCardTypes Method (QueryResultSettings, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetCardTypes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getcardtypes(v=AX.60)
ms:contentKeyID: 65321198
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCardTypes Method (QueryResultSettings, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCardTypes ( _
    settings As QueryResultSettings, _
    cardNumber As String _
) As PagedResult(Of CardTypeInfo)
'Usage
Dim instance As ChannelManager
Dim settings As QueryResultSettings
Dim cardNumber As String
Dim returnValue As PagedResult(Of CardTypeInfo)

returnValue = instance.GetCardTypes(settings, _
    cardNumber)
```

``` csharp
public PagedResult<CardTypeInfo> GetCardTypes(
    QueryResultSettings settings,
    string cardNumber
)
```

``` c++
public:
PagedResult<CardTypeInfo^>^ GetCardTypes(
    QueryResultSettings^ settings, 
    String^ cardNumber
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[CardTypeInfo](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetCardTypes Overload](channelmanager-getcardtypes-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

