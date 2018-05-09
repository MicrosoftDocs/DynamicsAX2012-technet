---
title: GetCitiesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetCitiesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCitiesDataRequest.#ctor(System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcitiesdatarequest.getcitiesdatarequest(v=AX.60)
ms:contentKeyID: 65322972
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCitiesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetCitiesDataRequest Constructor

Initializes a new instance of the [GetCitiesDataRequest](getcitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionCode As String, _
    stateId As String, _
    countyId As String, _
    settings As QueryResultSettings _
)
'Usage
Dim countryRegionCode As String
Dim stateId As String
Dim countyId As String
Dim settings As QueryResultSettings

Dim instance As New GetCitiesDataRequest(countryRegionCode, _
    stateId, countyId, settings)
```

``` csharp
public GetCitiesDataRequest(
    string countryRegionCode,
    string stateId,
    string countyId,
    QueryResultSettings settings
)
```

``` c++
public:
GetCitiesDataRequest(
    String^ countryRegionCode, 
    String^ stateId, 
    String^ countyId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countryRegionCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stateId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - countyId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetCitiesDataRequest Class](getcitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

