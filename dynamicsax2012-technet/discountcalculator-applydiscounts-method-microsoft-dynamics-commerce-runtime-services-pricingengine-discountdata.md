---
title: DiscountCalculator.ApplyDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ApplyDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountCalculator.ApplyDiscounts(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountcalculator.applydiscounts(v=AX.60)
ms:contentKeyID: 62207052
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountCalculator.ApplyDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# ApplyDiscounts Method

Determine the best set of discounts to apply to the specified transaction, and apply those discounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Sub ApplyDiscounts ( _
    transaction As SalesTransaction _
)
'Usage
Dim instance As DiscountCalculator
Dim transaction As SalesTransaction

instance.ApplyDiscounts(transaction)
```

``` csharp
public void ApplyDiscounts(
    SalesTransaction transaction
)
```

``` c++
public:
void ApplyDiscounts(
    SalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[DiscountCalculator Class](discountcalculator-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

