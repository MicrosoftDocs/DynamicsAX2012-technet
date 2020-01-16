---
title: StoreProductAvailabilityController.GetListingAvailableQuantity Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetListingAvailableQuantity Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.StoreProductAvailabilityController.GetListingAvailableQuantity(System.Collections.Generic.IEnumerable{System.Int64},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.storeproductavailabilitycontroller.getlistingavailablequantity(v=AX.60)
ms:contentKeyID: 65315703
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.StoreProductAvailabilityController.GetListingAvailableQuantity
dev_langs:
- CSharp
- C++
- VB
---

# GetListingAvailableQuantity Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetListingAvailableQuantity ( _
    listingIds As IEnumerable(Of Long), _
    customerId As String _
) As IEnumerable(Of ListingAvailableQuantity)
'Usage
Dim instance As StoreProductAvailabilityController
Dim listingIds As IEnumerable(Of Long)
Dim customerId As String
Dim returnValue As IEnumerable(Of ListingAvailableQuantity)

returnValue = instance.GetListingAvailableQuantity(listingIds, _
    customerId)
```

``` csharp
public virtual IEnumerable<ListingAvailableQuantity> GetListingAvailableQuantity(
    IEnumerable<long> listingIds,
    string customerId
)
```

``` c++
public:
virtual IEnumerable<ListingAvailableQuantity^>^ GetListingAvailableQuantity(
    IEnumerable<long long>^ listingIds, 
    String^ customerId
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingAvailableQuantity](listingavailablequantity-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[StoreProductAvailabilityController Class](storeproductavailabilitycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

