---
title: GetDistrictServiceRequest Constructor (String, String, String, String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetDistrictServiceRequest Constructor (String, String, String, String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDistrictServiceRequest.#ctor(System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getdistrictservicerequest.getdistrictservicerequest(v=AX.60)
ms:contentKeyID: 65322892
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDistrictServiceRequest Constructor (String, String, String, String, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionId As String, _
    stateId As String, _
    countyId As String, _
    city As String, _
    settings As QueryResultSettings _
)
'Usage
Dim countryRegionId As String
Dim stateId As String
Dim countyId As String
Dim city As String
Dim settings As QueryResultSettings

Dim instance As New GetDistrictServiceRequest(countryRegionId, _
    stateId, countyId, city, settings)
```

``` csharp
public GetDistrictServiceRequest(
    string countryRegionId,
    string stateId,
    string countyId,
    string city,
    QueryResultSettings settings
)
```

``` c++
public:
GetDistrictServiceRequest(
    String^ countryRegionId, 
    String^ stateId, 
    String^ countyId, 
    String^ city, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countryRegionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stateId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - countyId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - city  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetDistrictServiceRequest Class](getdistrictservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetDistrictServiceRequest Overload](getdistrictservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

