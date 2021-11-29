---
title: StoreProductAvailabilityServiceBase.GetNearbyStoresWithAvailability Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetNearbyStoresWithAvailability Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityServiceBase.GetNearbyStoresWithAvailability(System.Decimal,System.Decimal,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.storeproductavailabilityservicebase.getnearbystoreswithavailability(v=AX.60)
ms:contentKeyID: 65316986
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityServiceBase.GetNearbyStoresWithAvailability
dev_langs:
- CSharp
- C++
- VB
---

# GetNearbyStoresWithAvailability Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetNearbyStoresWithAvailability ( _
    latitude As Decimal, _
    longitude As Decimal, _
    items As IEnumerable(Of TransactionItem) _
) As StoreProductAvailabilityResponse
'Usage
Dim instance As StoreProductAvailabilityServiceBase
Dim latitude As Decimal
Dim longitude As Decimal
Dim items As IEnumerable(Of TransactionItem)
Dim returnValue As StoreProductAvailabilityResponse

returnValue = instance.GetNearbyStoresWithAvailability(latitude, _
    longitude, items)
```

``` csharp
public virtual StoreProductAvailabilityResponse GetNearbyStoresWithAvailability(
    decimal latitude,
    decimal longitude,
    IEnumerable<TransactionItem> items
)
```

``` c++
public:
virtual StoreProductAvailabilityResponse^ GetNearbyStoresWithAvailability(
    Decimal latitude, 
    Decimal longitude, 
    IEnumerable<TransactionItem^>^ items
)
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TransactionItem](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityResponse](storeproductavailabilityresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IStoreProductAvailabilityService.GetNearbyStoresWithAvailability(Decimal, Decimal, IEnumerable\<TransactionItem\>)](istoreproductavailabilityservice-getnearbystoreswithavailability-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[StoreProductAvailabilityServiceBase Class](storeproductavailabilityservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

