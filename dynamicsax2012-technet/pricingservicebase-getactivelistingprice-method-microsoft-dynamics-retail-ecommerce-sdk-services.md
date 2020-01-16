---
title: PricingServiceBase.GetActiveListingPrice Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetActiveListingPrice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase.GetActiveListingPrice(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.pricingservicebase.getactivelistingprice(v=AX.60)
ms:contentKeyID: 65318207
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase.GetActiveListingPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveListingPrice Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetActiveListingPrice ( _
    listingIds As IEnumerable(Of Long) _
) As ListingPriceResponse
'Usage
Dim instance As PricingServiceBase
Dim listingIds As IEnumerable(Of Long)
Dim returnValue As ListingPriceResponse

returnValue = instance.GetActiveListingPrice(listingIds)
```

``` csharp
public virtual ListingPriceResponse GetActiveListingPrice(
    IEnumerable<long> listingIds
)
```

``` c++
public:
virtual ListingPriceResponse^ GetActiveListingPrice(
    IEnumerable<long long>^ listingIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IPricingService.GetActiveListingPrice(IEnumerable\<Int64\>)](ipricingservice-getactivelistingprice-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[PricingServiceBase Class](pricingservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

