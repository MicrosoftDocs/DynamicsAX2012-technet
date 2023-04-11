---
title: GetStoresServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetStoresServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstoresservicerequest.getstoresservicerequest(v=AX.60)
ms:contentKeyID: 65322097
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetStoresServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    channelId As Long, _
    searchArea As SearchArea _
)
'Usage
Dim settings As QueryResultSettings
Dim channelId As Long
Dim searchArea As SearchArea

Dim instance As New GetStoresServiceRequest(settings, _
    channelId, searchArea)
```

``` csharp
public GetStoresServiceRequest(
    QueryResultSettings settings,
    long channelId,
    SearchArea searchArea
)
```

``` c++
public:
GetStoresServiceRequest(
    QueryResultSettings^ settings, 
    long long channelId, 
    SearchArea^ searchArea
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - searchArea  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetStoresServiceRequest Class](getstoresservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

