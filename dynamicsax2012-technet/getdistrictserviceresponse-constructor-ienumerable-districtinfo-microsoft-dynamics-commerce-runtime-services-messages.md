---
title: GetDistrictServiceResponse Constructor (IEnumerable(DistrictInfo)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetDistrictServiceResponse Constructor (IEnumerable(DistrictInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDistrictServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DistrictInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getdistrictserviceresponse.getdistrictserviceresponse(v=AX.60)
ms:contentKeyID: 62214281
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDistrictServiceResponse Constructor (IEnumerable(DistrictInfo))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetDistrictServiceResponse](getdistrictserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    districts As IEnumerable(Of DistrictInfo) _
)
'Usage
Dim districts As IEnumerable(Of DistrictInfo)

Dim instance As New GetDistrictServiceResponse(districts)
```

``` csharp
public GetDistrictServiceResponse(
    IEnumerable<DistrictInfo> districts
)
```

``` c++
public:
GetDistrictServiceResponse(
    IEnumerable<DistrictInfo^>^ districts
)
```

#### Parameters

  - districts  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DistrictInfo](districtinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetDistrictServiceResponse Class](getdistrictserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetDistrictServiceResponse Overload](getdistrictserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

