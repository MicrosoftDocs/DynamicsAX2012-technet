---
title: StoreProductAvailabilityController.GetNearbyStoresWithAvailability Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetNearbyStoresWithAvailability Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.StoreProductAvailabilityController.GetNearbyStoresWithAvailability(System.Decimal,System.Decimal,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.storeproductavailabilitycontroller.getnearbystoreswithavailability(v=AX.60)
ms:contentKeyID: 65315662
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.StoreProductAvailabilityController.GetNearbyStoresWithAvailability
dev_langs:
- CSharp
- C++
- VB
---

# GetNearbyStoresWithAvailability Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetNearbyStoresWithAvailability ( _
    latitude As Decimal, _
    longitude As Decimal, _
    shoppingCartItems As IEnumerable(Of TransactionItem) _
) As Collection(Of StoreProductAvailability)
'Usage
Dim instance As StoreProductAvailabilityController
Dim latitude As Decimal
Dim longitude As Decimal
Dim shoppingCartItems As IEnumerable(Of TransactionItem)
Dim returnValue As Collection(Of StoreProductAvailability)

returnValue = instance.GetNearbyStoresWithAvailability(latitude, _
    longitude, shoppingCartItems)
```

``` csharp
public virtual Collection<StoreProductAvailability> GetNearbyStoresWithAvailability(
    decimal latitude,
    decimal longitude,
    IEnumerable<TransactionItem> shoppingCartItems
)
```

``` c++
public:
virtual Collection<StoreProductAvailability^>^ GetNearbyStoresWithAvailability(
    Decimal latitude, 
    Decimal longitude, 
    IEnumerable<TransactionItem^>^ shoppingCartItems
)
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - shoppingCartItems  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TransactionItem](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[StoreProductAvailability](storeproductavailability-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[StoreProductAvailabilityController Class](storeproductavailabilitycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

