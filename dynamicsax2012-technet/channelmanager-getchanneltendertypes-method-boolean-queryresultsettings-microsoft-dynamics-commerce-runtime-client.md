---
title: ChannelManager.GetChannelTenderTypes Method (Boolean, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelTenderTypes Method (Boolean, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelTenderTypes(System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getchanneltendertypes(v=AX.60)
ms:contentKeyID: 65319392
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelTenderTypes Method (Boolean, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelTenderTypes ( _
    countingRequired As Boolean, _
    settings As QueryResultSettings _
) As PagedResult(Of TenderType)
'Usage
Dim instance As ChannelManager
Dim countingRequired As Boolean
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of TenderType)

returnValue = instance.GetChannelTenderTypes(countingRequired, _
    settings)
```

``` csharp
public PagedResult<TenderType> GetChannelTenderTypes(
    bool countingRequired,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<TenderType^>^ GetChannelTenderTypes(
    bool countingRequired, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countingRequired  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[TenderType](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetChannelTenderTypes Overload](channelmanager-getchanneltendertypes-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

