---
title: GetShippingRateFromCarrierServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetShippingRateFromCarrierServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShippingRateFromCarrierServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.ParameterSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshippingratefromcarrierservicerequest.getshippingratefromcarrierservicerequest(v=AX.60)
ms:contentKeyID: 65321774
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShippingRateFromCarrierServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetShippingRateFromCarrierServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    adapterConfig As ParameterSet, _
    shippingRateInfo As ShippingRateInfo _
)
'Usage
Dim adapterConfig As ParameterSet
Dim shippingRateInfo As ShippingRateInfo

Dim instance As New GetShippingRateFromCarrierServiceRequest(adapterConfig, _
    shippingRateInfo)
```

``` csharp
public GetShippingRateFromCarrierServiceRequest(
    ParameterSet adapterConfig,
    ShippingRateInfo shippingRateInfo
)
```

``` c++
public:
GetShippingRateFromCarrierServiceRequest(
    ParameterSet^ adapterConfig, 
    ShippingRateInfo^ shippingRateInfo
)
```

#### Parameters

  - adapterConfig  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - shippingRateInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo](shippingrateinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetShippingRateFromCarrierServiceRequest Class](getshippingratefromcarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

