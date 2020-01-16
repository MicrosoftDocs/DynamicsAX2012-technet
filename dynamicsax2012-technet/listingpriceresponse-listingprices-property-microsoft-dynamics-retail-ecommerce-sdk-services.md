---
title: ListingPriceResponse.ListingPrices Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ListingPrices Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse.ListingPrices
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.listingpriceresponse.listingprices(v=AX.60)
ms:contentKeyID: 65316460
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse.ListingPrices
dev_langs:
- CSharp
- C++
- VB
---

# ListingPrices Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingPrices As IEnumerable(Of ListingPrice)
    Get
    Set
'Usage
Dim instance As ListingPriceResponse
Dim value As IEnumerable(Of ListingPrice)

value = instance.ListingPrices

instance.ListingPrices = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ListingPrice> ListingPrices { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ListingPrice^>^ ListingPrices {
    IEnumerable<ListingPrice^>^ get ();
    void set (IEnumerable<ListingPrice^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingPrice](listingprice-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[ListingPriceResponse Class](listingpriceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

