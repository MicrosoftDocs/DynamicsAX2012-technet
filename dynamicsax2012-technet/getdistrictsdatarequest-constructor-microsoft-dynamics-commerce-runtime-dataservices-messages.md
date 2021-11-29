---
title: GetDistrictsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetDistrictsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDistrictsDataRequest.#ctor(System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdistrictsdatarequest.getdistrictsdatarequest(v=AX.60)
ms:contentKeyID: 65319079
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDistrictsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetDistrictsDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetDistrictsDataRequest](getdistrictsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionCode As String, _
    stateId As String, _
    countyId As String, _
    city As String, _
    settings As QueryResultSettings _
)
'Usage
Dim countryRegionCode As String
Dim stateId As String
Dim countyId As String
Dim city As String
Dim settings As QueryResultSettings

Dim instance As New GetDistrictsDataRequest(countryRegionCode, _
    stateId, countyId, city, settings)
```

``` csharp
public GetDistrictsDataRequest(
    string countryRegionCode,
    string stateId,
    string countyId,
    string city,
    QueryResultSettings settings
)
```

``` c++
public:
GetDistrictsDataRequest(
    String^ countryRegionCode, 
    String^ stateId, 
    String^ countyId, 
    String^ city, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countryRegionCode  
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

[GetDistrictsDataRequest Class](getdistrictsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

