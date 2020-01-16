---
title: StoreProductAvailabilityServiceBase.GetListingAvailableQuantities Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetListingAvailableQuantities Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityServiceBase.GetListingAvailableQuantities(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.storeproductavailabilityservicebase.getlistingavailablequantities(v=AX.60)
ms:contentKeyID: 65317457
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityServiceBase.GetListingAvailableQuantities
dev_langs:
- CSharp
- C++
- VB
---

# GetListingAvailableQuantities Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetListingAvailableQuantities ( _
    listingIds As IEnumerable(Of Long) _
) As ListingAvailableQuantityResponse
'Usage
Dim instance As StoreProductAvailabilityServiceBase
Dim listingIds As IEnumerable(Of Long)
Dim returnValue As ListingAvailableQuantityResponse

returnValue = instance.GetListingAvailableQuantities(listingIds)
```

``` csharp
public virtual ListingAvailableQuantityResponse GetListingAvailableQuantities(
    IEnumerable<long> listingIds
)
```

``` c++
public:
virtual ListingAvailableQuantityResponse^ GetListingAvailableQuantities(
    IEnumerable<long long>^ listingIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingAvailableQuantityResponse](listingavailablequantityresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IStoreProductAvailabilityService.GetListingAvailableQuantities(IEnumerable\<Int64\>)](istoreproductavailabilityservice-getlistingavailablequantities-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[StoreProductAvailabilityServiceBase Class](storeproductavailabilityservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

