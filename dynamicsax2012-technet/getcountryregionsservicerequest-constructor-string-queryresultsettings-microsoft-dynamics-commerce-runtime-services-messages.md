---
title: GetCountryRegionsServiceRequest Constructor (String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCountryRegionsServiceRequest Constructor (String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountryRegionsServiceRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcountryregionsservicerequest.getcountryregionsservicerequest(v=AX.60)
ms:contentKeyID: 65318803
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCountryRegionsServiceRequest Constructor (String, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    languageId As String, _
    settings As QueryResultSettings _
)
'Usage
Dim languageId As String
Dim settings As QueryResultSettings

Dim instance As New GetCountryRegionsServiceRequest(languageId, _
    settings)
```

``` csharp
public GetCountryRegionsServiceRequest(
    string languageId,
    QueryResultSettings settings
)
```

``` c++
public:
GetCountryRegionsServiceRequest(
    String^ languageId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetCountryRegionsServiceRequest Class](getcountryregionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCountryRegionsServiceRequest Overload](getcountryregionsservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

