---
title: IndiaPriceHelper.GetIndiaPriceHelper Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetIndiaPriceHelper Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.IndiaPriceHelper.GetIndiaPriceHelper(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.indiapricehelper.getindiapricehelper(v=AX.60)
ms:contentKeyID: 65321935
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.IndiaPriceHelper.GetIndiaPriceHelper
dev_langs:
- CSharp
- C++
- VB
---

# GetIndiaPriceHelper Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetIndiaPriceHelper ( _
    context As RequestContext, _
    pricingDataManager As IPricingDataManagerV2 _
) As IndiaPriceHelper
'Usage
Dim context As RequestContext
Dim pricingDataManager As IPricingDataManagerV2
Dim returnValue As IndiaPriceHelper

returnValue = IndiaPriceHelper.GetIndiaPriceHelper(context, _
    pricingDataManager)
```

``` csharp
public static IndiaPriceHelper GetIndiaPriceHelper(
    RequestContext context,
    IPricingDataManagerV2 pricingDataManager
)
```

``` c++
public:
static IndiaPriceHelper^ GetIndiaPriceHelper(
    RequestContext^ context, 
    IPricingDataManagerV2^ pricingDataManager
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.IndiaPriceHelper](indiapricehelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

## See Also

#### Reference

[IndiaPriceHelper Class](indiapricehelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

