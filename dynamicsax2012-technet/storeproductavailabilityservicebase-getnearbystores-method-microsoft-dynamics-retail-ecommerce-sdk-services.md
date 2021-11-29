---
title: StoreProductAvailabilityServiceBase.GetNearbyStores Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetNearbyStores Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityServiceBase.GetNearbyStores(System.Decimal,System.Decimal,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.storeproductavailabilityservicebase.getnearbystores(v=AX.60)
ms:contentKeyID: 65316005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityServiceBase.GetNearbyStores
dev_langs:
- CSharp
- C++
- VB
---

# GetNearbyStores Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetNearbyStores ( _
    latitude As Decimal, _
    longitude As Decimal, _
    distance As Integer _
) As StoreLocationResponse
'Usage
Dim instance As StoreProductAvailabilityServiceBase
Dim latitude As Decimal
Dim longitude As Decimal
Dim distance As Integer
Dim returnValue As StoreLocationResponse

returnValue = instance.GetNearbyStores(latitude, _
    longitude, distance)
```

``` csharp
public virtual StoreLocationResponse GetNearbyStores(
    decimal latitude,
    decimal longitude,
    int distance
)
```

``` c++
public:
virtual StoreLocationResponse^ GetNearbyStores(
    Decimal latitude, 
    Decimal longitude, 
    int distance
)
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - distance  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreLocationResponse](storelocationresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IStoreProductAvailabilityService.GetNearbyStores(Decimal, Decimal, Int32)](istoreproductavailabilityservice-getnearbystores-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[StoreProductAvailabilityServiceBase Class](storeproductavailabilityservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

