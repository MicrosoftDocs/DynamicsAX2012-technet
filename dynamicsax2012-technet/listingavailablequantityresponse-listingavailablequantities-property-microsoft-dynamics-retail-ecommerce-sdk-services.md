---
title: ListingAvailableQuantityResponse.ListingAvailableQuantities Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ListingAvailableQuantities Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingAvailableQuantityResponse.ListingAvailableQuantities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.listingavailablequantityresponse.listingavailablequantities(v=AX.60)
ms:contentKeyID: 65317839
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingAvailableQuantityResponse.ListingAvailableQuantities
dev_langs:
- CSharp
- C++
- VB
---

# ListingAvailableQuantities Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingAvailableQuantities As IEnumerable(Of ListingAvailableQuantity)
    Get
    Set
'Usage
Dim instance As ListingAvailableQuantityResponse
Dim value As IEnumerable(Of ListingAvailableQuantity)

value = instance.ListingAvailableQuantities

instance.ListingAvailableQuantities = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ListingAvailableQuantity> ListingAvailableQuantities { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ListingAvailableQuantity^>^ ListingAvailableQuantities {
    IEnumerable<ListingAvailableQuantity^>^ get ();
    void set (IEnumerable<ListingAvailableQuantity^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingAvailableQuantity](listingavailablequantity-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[ListingAvailableQuantityResponse Class](listingavailablequantityresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

