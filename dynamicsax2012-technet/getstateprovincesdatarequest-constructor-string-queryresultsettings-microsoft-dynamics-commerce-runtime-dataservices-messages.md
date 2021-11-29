---
title: GetStateProvincesDataRequest Constructor (String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetStateProvincesDataRequest Constructor (String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStateProvincesDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getstateprovincesdatarequest.getstateprovincesdatarequest(v=AX.60)
ms:contentKeyID: 65315838
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStateProvincesDataRequest Constructor (String, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetStateProvincesDataRequest](getstateprovincesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionCode As String, _
    settings As QueryResultSettings _
)
'Usage
Dim countryRegionCode As String
Dim settings As QueryResultSettings

Dim instance As New GetStateProvincesDataRequest(countryRegionCode, _
    settings)
```

``` csharp
public GetStateProvincesDataRequest(
    string countryRegionCode,
    QueryResultSettings settings
)
```

``` c++
public:
GetStateProvincesDataRequest(
    String^ countryRegionCode, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countryRegionCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetStateProvincesDataRequest Class](getstateprovincesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetStateProvincesDataRequest Overload](getstateprovincesdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

