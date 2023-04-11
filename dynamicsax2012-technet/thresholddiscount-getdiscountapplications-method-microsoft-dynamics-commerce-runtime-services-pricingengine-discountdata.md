---
title: ThresholdDiscount.GetDiscountApplications Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: GetDiscountApplications Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.ThresholdDiscount.GetDiscountApplications(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup[],System.Decimal[],System.Collections.Generic.IEnumerable{System.Int64},System.String,Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.thresholddiscount.getdiscountapplications(v=AX.60)
ms:contentKeyID: 62209288
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.ThresholdDiscount.GetDiscountApplications
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountApplications Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all of the possible applications of this discount to the specified transaction and line items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function GetDiscountApplications ( _
    transaction As SalesTransaction, _
    discountableItemGroups As DiscountableItemGroup(), _
    remainingQuantities As Decimal(), _
    storePriceGroups As IEnumerable(Of Long), _
    currencyCode As String, _
    pricingDataManager As IPricingDataManagerV2, _
    isReturn As Boolean, _
    priceContext As PriceContext _
) As IEnumerable(Of DiscountApplication)
'Usage
Dim instance As ThresholdDiscount
Dim transaction As SalesTransaction
Dim discountableItemGroups As DiscountableItemGroup()
Dim remainingQuantities As Decimal()
Dim storePriceGroups As IEnumerable(Of Long)
Dim currencyCode As String
Dim pricingDataManager As IPricingDataManagerV2
Dim isReturn As Boolean
Dim priceContext As PriceContext
Dim returnValue As IEnumerable(Of DiscountApplication)

returnValue = instance.GetDiscountApplications(transaction, _
    discountableItemGroups, remainingQuantities, _
    storePriceGroups, currencyCode, _
    pricingDataManager, isReturn, priceContext)
```

``` csharp
public override IEnumerable<DiscountApplication> GetDiscountApplications(
    SalesTransaction transaction,
    DiscountableItemGroup[] discountableItemGroups,
    decimal[] remainingQuantities,
    IEnumerable<long> storePriceGroups,
    string currencyCode,
    IPricingDataManagerV2 pricingDataManager,
    bool isReturn,
    PriceContext priceContext
)
```

``` c++
public:
virtual IEnumerable<DiscountApplication^>^ GetDiscountApplications(
    SalesTransaction^ transaction, 
    array<DiscountableItemGroup^>^ discountableItemGroups, 
    array<Decimal>^ remainingQuantities, 
    IEnumerable<long long>^ storePriceGroups, 
    String^ currencyCode, 
    IPricingDataManagerV2^ pricingDataManager, 
    bool isReturn, 
    PriceContext^ priceContext
) override
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - discountableItemGroups  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\[\]  

<!-- end list -->

  - remainingQuantities  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\[\]  

<!-- end list -->

  - storePriceGroups  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - isReturn  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DiscountApplication](discountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>  
The possible permutations of line items that this discount can apply to, or an empty collection if this discount cannot apply.  

## See Also

#### Reference

[ThresholdDiscount Class](thresholddiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

