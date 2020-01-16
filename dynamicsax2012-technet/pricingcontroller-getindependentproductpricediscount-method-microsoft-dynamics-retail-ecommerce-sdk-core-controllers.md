---
title: PricingController.GetIndependentProductPriceDiscount Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetIndependentProductPriceDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.PricingController.GetIndependentProductPriceDiscount(System.Collections.Generic.IEnumerable{System.Int64},System.Int64,System.Nullable{System.Int64},System.String,System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.pricingcontroller.getindependentproductpricediscount(v=AX.60)
ms:contentKeyID: 65316753
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.PricingController.GetIndependentProductPriceDiscount
dev_langs:
- CSharp
- C++
- VB
---

# GetIndependentProductPriceDiscount Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetIndependentProductPriceDiscount ( _
    productIds As IEnumerable(Of Long), _
    channelId As Long, _
    catalogId As Nullable(Of Long), _
    customerId As String, _
    affiliationLoyaltyTierIds As IEnumerable(Of Long) _
) As ReadOnlyCollection(Of ListingPrice)
'Usage
Dim instance As PricingController
Dim productIds As IEnumerable(Of Long)
Dim channelId As Long
Dim catalogId As Nullable(Of Long)
Dim customerId As String
Dim affiliationLoyaltyTierIds As IEnumerable(Of Long)
Dim returnValue As ReadOnlyCollection(Of ListingPrice)

returnValue = instance.GetIndependentProductPriceDiscount(productIds, _
    channelId, catalogId, customerId, _
    affiliationLoyaltyTierIds)
```

``` csharp
public virtual ReadOnlyCollection<ListingPrice> GetIndependentProductPriceDiscount(
    IEnumerable<long> productIds,
    long channelId,
    Nullable<long> catalogId,
    string customerId,
    IEnumerable<long> affiliationLoyaltyTierIds
)
```

``` c++
public:
virtual ReadOnlyCollection<ListingPrice^>^ GetIndependentProductPriceDiscount(
    IEnumerable<long long>^ productIds, 
    long long channelId, 
    Nullable<long long> catalogId, 
    String^ customerId, 
    IEnumerable<long long>^ affiliationLoyaltyTierIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - affiliationLoyaltyTierIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ListingPrice](listingprice-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[PricingController Class](pricingcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

