---
title: GetStateProvincesServiceRequest Constructor (String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetStateProvincesServiceRequest Constructor (String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStateProvincesServiceRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstateprovincesservicerequest.getstateprovincesservicerequest(v=AX.60)
ms:contentKeyID: 65320481
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStateProvincesServiceRequest Constructor (String, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionId As String, _
    settings As QueryResultSettings _
)
'Usage
Dim countryRegionId As String
Dim settings As QueryResultSettings

Dim instance As New GetStateProvincesServiceRequest(countryRegionId, _
    settings)
```

``` csharp
public GetStateProvincesServiceRequest(
    string countryRegionId,
    QueryResultSettings settings
)
```

``` c++
public:
GetStateProvincesServiceRequest(
    String^ countryRegionId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countryRegionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetStateProvincesServiceRequest Class](getstateprovincesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetStateProvincesServiceRequest Overload](getstateprovincesservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

