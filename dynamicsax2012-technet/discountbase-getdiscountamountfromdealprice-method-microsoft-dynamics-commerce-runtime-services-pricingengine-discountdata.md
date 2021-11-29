---
title: DiscountBase.GetDiscountAmountFromDealPrice Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: GetDiscountAmountFromDealPrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetDiscountAmountFromDealPrice(System.Decimal,System.Boolean,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.getdiscountamountfromdealprice(v=AX.60)
ms:contentKeyID: 65319670
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetDiscountAmountFromDealPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountAmountFromDealPrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function GetDiscountAmountFromDealPrice ( _
    price As Decimal, _
    hasExistingDealPrice As Boolean, _
    bestExistingDealPrice As Decimal, _
    dealPrice As Decimal _
) As Decimal
'Usage
Dim price As Decimal
Dim hasExistingDealPrice As Boolean
Dim bestExistingDealPrice As Decimal
Dim dealPrice As Decimal
Dim returnValue As Decimal

returnValue = DiscountBase.GetDiscountAmountFromDealPrice(price, _
    hasExistingDealPrice, bestExistingDealPrice, _
    dealPrice)
```

``` csharp
protected static decimal GetDiscountAmountFromDealPrice(
    decimal price,
    bool hasExistingDealPrice,
    decimal bestExistingDealPrice,
    decimal dealPrice
)
```

``` c++
protected:
static Decimal GetDiscountAmountFromDealPrice(
    Decimal price, 
    bool hasExistingDealPrice, 
    Decimal bestExistingDealPrice, 
    Decimal dealPrice
)
```

#### Parameters

  - price  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - hasExistingDealPrice  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - bestExistingDealPrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - dealPrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

