---
title: GetExternalShippingRateServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetExternalShippingRateServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineShippingRate})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getexternalshippingrateserviceresponse.getexternalshippingrateserviceresponse(v=AX.60)
ms:contentKeyID: 49845711
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetExternalShippingRateServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetExternalShippingRateServiceResponse](getexternalshippingrateserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLineShippingRates As IEnumerable(Of SalesLineShippingRate) _
)
'Usage
Dim salesLineShippingRates As IEnumerable(Of SalesLineShippingRate)

Dim instance As New GetExternalShippingRateServiceResponse(salesLineShippingRates)
```

``` csharp
public GetExternalShippingRateServiceResponse(
    IEnumerable<SalesLineShippingRate> salesLineShippingRates
)
```

``` c++
public:
GetExternalShippingRateServiceResponse(
    IEnumerable<SalesLineShippingRate^>^ salesLineShippingRates
)
```

#### Parameters

  - salesLineShippingRates  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLineShippingRate](saleslineshippingrate-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetExternalShippingRateServiceResponse Class](getexternalshippingrateserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

