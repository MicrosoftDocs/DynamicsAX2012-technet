---
title: GetStateProvincesServiceResponse Constructor (IEnumerable(StateProvinceInfo)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetStateProvincesServiceResponse Constructor (IEnumerable(StateProvinceInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStateProvincesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StateProvinceInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstateprovincesserviceresponse.getstateprovincesserviceresponse(v=AX.60)
ms:contentKeyID: 62211418
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStateProvincesServiceResponse Constructor (IEnumerable(StateProvinceInfo))

Initializes a new instance of the [GetStateProvincesServiceResponse](getstateprovincesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    states As IEnumerable(Of StateProvinceInfo) _
)
'Usage
Dim states As IEnumerable(Of StateProvinceInfo)

Dim instance As New GetStateProvincesServiceResponse(states)
```

``` csharp
public GetStateProvincesServiceResponse(
    IEnumerable<StateProvinceInfo> states
)
```

``` c++
public:
GetStateProvincesServiceResponse(
    IEnumerable<StateProvinceInfo^>^ states
)
```

#### Parameters

  - states  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StateProvinceInfo](stateprovinceinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStateProvincesServiceResponse Class](getstateprovincesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetStateProvincesServiceResponse Overload](getstateprovincesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

