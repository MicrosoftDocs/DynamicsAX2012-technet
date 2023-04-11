---
title: GetStoreLocationsRequest Constructor (QueryResultSettings, SearchArea) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoreLocationsRequest Constructor (QueryResultSettings, SearchArea)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstorelocationsrequest.getstorelocationsrequest(v=AX.60)
ms:contentKeyID: 65316879
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreLocationsRequest Constructor (QueryResultSettings, SearchArea)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    searchArea As SearchArea _
)
'Usage
Dim settings As QueryResultSettings
Dim searchArea As SearchArea

Dim instance As New GetStoreLocationsRequest(settings, _
    searchArea)
```

``` csharp
public GetStoreLocationsRequest(
    QueryResultSettings settings,
    SearchArea searchArea
)
```

``` c++
public:
GetStoreLocationsRequest(
    QueryResultSettings^ settings, 
    SearchArea^ searchArea
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - searchArea  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetStoreLocationsRequest Class](getstorelocationsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoreLocationsRequest Overload](getstorelocationsrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

