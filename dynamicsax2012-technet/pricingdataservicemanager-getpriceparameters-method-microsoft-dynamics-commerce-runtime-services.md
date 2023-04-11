---
title: PricingDataServiceManager.GetPriceParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetPriceParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetPriceParameters(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getpriceparameters(v=AX.60)
ms:contentKeyID: 65316935
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetPriceParameters
dev_langs:
- CSharp
- C++
- VB
---

# GetPriceParameters Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetPriceParameters ( _
    columns As ColumnSet _
) As PriceParameters
'Usage
Dim instance As PricingDataServiceManager
Dim columns As ColumnSet
Dim returnValue As PriceParameters

returnValue = instance.GetPriceParameters(columns)
```

``` csharp
public PriceParameters GetPriceParameters(
    ColumnSet columns
)
```

``` c++
public:
virtual PriceParameters^ GetPriceParameters(
    ColumnSet^ columns
) sealed
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[IPricingDataManager.GetPriceParameters(ColumnSet)](ipricingdatamanager-getpriceparameters-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

