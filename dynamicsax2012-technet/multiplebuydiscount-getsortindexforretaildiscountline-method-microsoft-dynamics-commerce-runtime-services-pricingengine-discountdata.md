---
title: MultipleBuyDiscount.GetSortIndexForRetailDiscountLine Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: GetSortIndexForRetailDiscountLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.MultipleBuyDiscount.GetSortIndexForRetailDiscountLine(Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.multiplebuydiscount.getsortindexforretaildiscountline(v=AX.60)
ms:contentKeyID: 65318724
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.MultipleBuyDiscount.GetSortIndexForRetailDiscountLine
dev_langs:
- CSharp
- C++
- VB
---

# GetSortIndexForRetailDiscountLine Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This member overrides [DiscountBase.GetSortIndexForRetailDiscountLine(RetailDiscountLine)](discountbase-getsortindexforretaildiscountline-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetSortIndexForRetailDiscountLine ( _
    line As RetailDiscountLine _
) As Integer
'Usage
Dim line As RetailDiscountLine
Dim returnValue As Integer

returnValue = Me.GetSortIndexForRetailDiscountLine(line)
```

``` csharp
protected override int GetSortIndexForRetailDiscountLine(
    RetailDiscountLine line
)
```

``` c++
protected:
virtual int GetSortIndexForRetailDiscountLine(
    RetailDiscountLine^ line
) override
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[MultipleBuyDiscount Class](multiplebuydiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

