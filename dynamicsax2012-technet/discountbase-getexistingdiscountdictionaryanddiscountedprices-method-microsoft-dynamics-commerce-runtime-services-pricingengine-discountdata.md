---
title: DiscountBase.GetExistingDiscountDictionaryAndDiscountedPrices Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: GetExistingDiscountDictionaryAndDiscountedPrices Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetExistingDiscountDictionaryAndDiscountedPrices(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup[],System.Decimal[],System.Collections.Generic.Stack{Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.AppliedDiscountApplication},Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication,System.Decimal[]@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.getexistingdiscountdictionaryanddiscountedprices(v=AX.60)
ms:contentKeyID: 65321114
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetExistingDiscountDictionaryAndDiscountedPrices
dev_langs:
- CSharp
- C++
- VB
---

# GetExistingDiscountDictionaryAndDiscountedPrices Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function GetExistingDiscountDictionaryAndDiscountedPrices ( _
    discountableItemGroups As DiscountableItemGroup(), _
    remainingQuantities As Decimal(), _
    appliedDiscounts As Stack(Of AppliedDiscountApplication), _
    discountApplication As DiscountApplication, _
    <OutAttribute> ByRef discountedPrices As Decimal() _
) As Dictionary(Of Integer, IList(Of DiscountLineQuantity))
'Usage
Dim discountableItemGroups As DiscountableItemGroup()
Dim remainingQuantities As Decimal()
Dim appliedDiscounts As Stack(Of AppliedDiscountApplication)
Dim discountApplication As DiscountApplication
Dim discountedPrices As Decimal()
Dim returnValue As Dictionary(Of Integer, IList(Of DiscountLineQuantity))

returnValue = Me.GetExistingDiscountDictionaryAndDiscountedPrices(discountableItemGroups, _
    remainingQuantities, appliedDiscounts, _
    discountApplication, discountedPrices)
```

``` csharp
protected Dictionary<int, IList<DiscountLineQuantity>> GetExistingDiscountDictionaryAndDiscountedPrices(
    DiscountableItemGroup[] discountableItemGroups,
    decimal[] remainingQuantities,
    Stack<AppliedDiscountApplication> appliedDiscounts,
    DiscountApplication discountApplication,
    out decimal[] discountedPrices
)
```

``` c++
protected:
Dictionary<int, IList<DiscountLineQuantity^>^>^ GetExistingDiscountDictionaryAndDiscountedPrices(
    array<DiscountableItemGroup^>^ discountableItemGroups, 
    array<Decimal>^ remainingQuantities, 
    Stack<AppliedDiscountApplication^>^ appliedDiscounts, 
    DiscountApplication^ discountApplication, 
    [OutAttribute] array<Decimal>^% discountedPrices
)
```

#### Parameters

  - discountableItemGroups  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\[\]  

<!-- end list -->

  - remainingQuantities  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\[\]  

<!-- end list -->

  - appliedDiscounts  
    Type: [System.Collections.Generic.Stack](https://technet.microsoft.com/library/3278tedw\(v=ax.60\))\<[AppliedDiscountApplication](applieddiscountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>  

<!-- end list -->

  - discountApplication  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication](discountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  

<!-- end list -->

  - discountedPrices  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)), [IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[DiscountLineQuantity](discountlinequantity-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>\>  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

