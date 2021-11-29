---
title: DiscountParameters.CreateAndInitialize Method (IPricingDataManager) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CreateAndInitialize Method (IPricingDataManager)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountParameters.CreateAndInitialize(Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountparameters.createandinitialize(v=AX.60)
ms:contentKeyID: 49846705
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateAndInitialize Method (IPricingDataManager)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create a new DiscountParameters object and initialize from database if possible.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateAndInitialize ( _
    pricingDataManager As IPricingDataManager _
) As DiscountParameters
'Usage
Dim pricingDataManager As IPricingDataManager
Dim returnValue As DiscountParameters

returnValue = DiscountParameters.CreateAndInitialize(pricingDataManager)
```

``` csharp
public static DiscountParameters CreateAndInitialize(
    IPricingDataManager pricingDataManager
)
```

``` c++
public:
static DiscountParameters^ CreateAndInitialize(
    IPricingDataManager^ pricingDataManager
)
```

#### Parameters

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountParameters](discountparameters-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  
Newly fetched and initialized DiscountParameters object.  

## See Also

#### Reference

[DiscountParameters Class](discountparameters-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[CreateAndInitialize Overload](discountparameters-createandinitialize-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

