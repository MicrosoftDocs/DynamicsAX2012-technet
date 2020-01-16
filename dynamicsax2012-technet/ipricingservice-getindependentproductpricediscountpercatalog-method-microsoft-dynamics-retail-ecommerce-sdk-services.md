---
title: IPricingService.GetIndependentProductPriceDiscountPerCatalog Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetIndependentProductPriceDiscountPerCatalog Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IPricingService.GetIndependentProductPriceDiscountPerCatalog(System.Collections.Generic.IEnumerable{System.Int64},System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.ipricingservice.getindependentproductpricediscountpercatalog(v=AX.60)
ms:contentKeyID: 65317181
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IPricingService.GetIndependentProductPriceDiscountPerCatalog
dev_langs:
- CSharp
- C++
- VB
---

# GetIndependentProductPriceDiscountPerCatalog Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetIndependentProductPriceDiscountPerCatalog ( _
    listingIds As IEnumerable(Of Long), _
    channelId As Long, _
    catalogId As Long _
) As ListingPriceResponse
'Usage
Dim instance As IPricingService
Dim listingIds As IEnumerable(Of Long)
Dim channelId As Long
Dim catalogId As Long
Dim returnValue As ListingPriceResponse

returnValue = instance.GetIndependentProductPriceDiscountPerCatalog(listingIds, _
    channelId, catalogId)
```

``` csharp
[OperationContractAttribute]
ListingPriceResponse GetIndependentProductPriceDiscountPerCatalog(
    IEnumerable<long> listingIds,
    long channelId,
    long catalogId
)
```

``` c++
[OperationContractAttribute]
ListingPriceResponse^ GetIndependentProductPriceDiscountPerCatalog(
    IEnumerable<long long>^ listingIds, 
    long long channelId, 
    long long catalogId
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IPricingService Interface](ipricingservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

