---
title: IStoreProductAvailabilityService.GetListingAvailableQuantities Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetListingAvailableQuantities Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IStoreProductAvailabilityService.GetListingAvailableQuantities(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.istoreproductavailabilityservice.getlistingavailablequantities(v=AX.60)
ms:contentKeyID: 65316843
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IStoreProductAvailabilityService.GetListingAvailableQuantities
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
<OperationContractAttribute> _
Function GetListingAvailableQuantities ( _
    listingIds As IEnumerable(Of Long) _
) As ListingAvailableQuantityResponse
'Usage
Dim instance As IStoreProductAvailabilityService
Dim listingIds As IEnumerable(Of Long)
Dim returnValue As ListingAvailableQuantityResponse

returnValue = instance.GetListingAvailableQuantities(listingIds)
```

``` csharp
[OperationContractAttribute]
ListingAvailableQuantityResponse GetListingAvailableQuantities(
    IEnumerable<long> listingIds
)
```

``` c++
[OperationContractAttribute]
ListingAvailableQuantityResponse^ GetListingAvailableQuantities(
    IEnumerable<long long>^ listingIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingAvailableQuantityResponse](listingavailablequantityresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IStoreProductAvailabilityService Interface](istoreproductavailabilityservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

