---
title: IPricingService.GetIndependentProductPriceDiscount Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetIndependentProductPriceDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IPricingService.GetIndependentProductPriceDiscount(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.ipricingservice.getindependentproductpricediscount(v=AX.60)
ms:contentKeyID: 65318475
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IPricingService.GetIndependentProductPriceDiscount
dev_langs:
- CSharp
- C++
- VB
---

# GetIndependentProductPriceDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetIndependentProductPriceDiscount ( _
    listingIds As IEnumerable(Of Long) _
) As ListingPriceResponse
'Usage
Dim instance As IPricingService
Dim listingIds As IEnumerable(Of Long)
Dim returnValue As ListingPriceResponse

returnValue = instance.GetIndependentProductPriceDiscount(listingIds)
```

``` csharp
[OperationContractAttribute]
ListingPriceResponse GetIndependentProductPriceDiscount(
    IEnumerable<long> listingIds
)
```

``` c++
[OperationContractAttribute]
ListingPriceResponse^ GetIndependentProductPriceDiscount(
    IEnumerable<long long>^ listingIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IPricingService Interface](ipricingservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

