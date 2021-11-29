---
title: GetCountiesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetCountiesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountiesDataRequest.#ctor(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcountiesdatarequest.getcountiesdatarequest(v=AX.60)
ms:contentKeyID: 65320381
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountiesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetCountiesDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCountiesDataRequest](getcountiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionCode As String, _
    stateId As String, _
    settings As QueryResultSettings _
)
'Usage
Dim countryRegionCode As String
Dim stateId As String
Dim settings As QueryResultSettings

Dim instance As New GetCountiesDataRequest(countryRegionCode, _
    stateId, settings)
```

``` csharp
public GetCountiesDataRequest(
    string countryRegionCode,
    string stateId,
    QueryResultSettings settings
)
```

``` c++
public:
GetCountiesDataRequest(
    String^ countryRegionCode, 
    String^ stateId, 
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

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetCountiesDataRequest Class](getcountiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

