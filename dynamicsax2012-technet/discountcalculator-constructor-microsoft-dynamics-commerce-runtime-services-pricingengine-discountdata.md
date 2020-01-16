---
title: DiscountCalculator Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountCalculator Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountCalculator.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.String,Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountcalculator.discountcalculator(v=AX.60)
ms:contentKeyID: 62214144
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountCalculator.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCalculator Constructor

Initializes a new instance of the DiscountCalculator class for the specified transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transaction As SalesTransaction, _
    currencyCode As String, _
    priceContext As PriceContext, _
    pricingDataManager As IPricingDataManagerV2 _
)
'Usage
Dim transaction As SalesTransaction
Dim currencyCode As String
Dim priceContext As PriceContext
Dim pricingDataManager As IPricingDataManagerV2

Dim instance As New DiscountCalculator(transaction, _
    currencyCode, priceContext, pricingDataManager)
```

``` csharp
public DiscountCalculator(
    SalesTransaction transaction,
    string currencyCode,
    PriceContext priceContext,
    IPricingDataManagerV2 pricingDataManager
)
```

``` c++
public:
DiscountCalculator(
    SalesTransaction^ transaction, 
    String^ currencyCode, 
    PriceContext^ priceContext, 
    IPricingDataManagerV2^ pricingDataManager
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

<!-- end list -->

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DiscountCalculator Class](discountcalculator-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

