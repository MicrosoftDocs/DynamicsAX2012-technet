---
title: PricingController.GetActiveListingPrice Method (IEnumerable(Int64), Int64, Nullable(Int64), DateTime, String) (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetActiveListingPrice Method (IEnumerable(Int64), Int64, Nullable(Int64), DateTime, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.PricingController.GetActiveListingPrice(System.Collections.Generic.IEnumerable{System.Int64},System.Int64,System.Nullable{System.Int64},System.DateTime,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.pricingcontroller.getactivelistingprice(v=AX.60)
ms:contentKeyID: 65317584
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetActiveListingPrice Method (IEnumerable(Int64), Int64, Nullable(Int64), DateTime, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetActiveListingPrice ( _
    productIds As IEnumerable(Of Long), _
    channelId As Long, _
    catalogId As Nullable(Of Long), _
    activeDate As DateTime, _
    customerId As String _
) As ReadOnlyCollection(Of ListingPrice)
'Usage
Dim instance As PricingController
Dim productIds As IEnumerable(Of Long)
Dim channelId As Long
Dim catalogId As Nullable(Of Long)
Dim activeDate As DateTime
Dim customerId As String
Dim returnValue As ReadOnlyCollection(Of ListingPrice)

returnValue = instance.GetActiveListingPrice(productIds, _
    channelId, catalogId, activeDate, _
    customerId)
```

``` csharp
public virtual ReadOnlyCollection<ListingPrice> GetActiveListingPrice(
    IEnumerable<long> productIds,
    long channelId,
    Nullable<long> catalogId,
    DateTime activeDate,
    string customerId
)
```

``` c++
public:
virtual ReadOnlyCollection<ListingPrice^>^ GetActiveListingPrice(
    IEnumerable<long long>^ productIds, 
    long long channelId, 
    Nullable<long long> catalogId, 
    DateTime activeDate, 
    String^ customerId
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

  - activeDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ListingPrice](listingprice-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[PricingController Class](pricingcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[GetActiveListingPrice Overload](pricingcontroller-getactivelistingprice-method-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

