---
title: StoreLocationController.GetNearbyStores Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetNearbyStores Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.StoreLocationController.GetNearbyStores(System.Decimal,System.Decimal,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.storelocationcontroller.getnearbystores(v=AX.60)
ms:contentKeyID: 65317517
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.StoreLocationController.GetNearbyStores
dev_langs:
- CSharp
- C++
- VB
---

# GetNearbyStores Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetNearbyStores ( _
    latitude As Decimal, _
    longitude As Decimal, _
    distance As Integer _
) As Collection(Of StoreLocation)
'Usage
Dim latitude As Decimal
Dim longitude As Decimal
Dim distance As Integer
Dim returnValue As Collection(Of StoreLocation)

returnValue = StoreLocationController.GetNearbyStores(latitude, _
    longitude, distance)
```

``` csharp
public static Collection<StoreLocation> GetNearbyStores(
    decimal latitude,
    decimal longitude,
    int distance
)
```

``` c++
public:
static Collection<StoreLocation^>^ GetNearbyStores(
    Decimal latitude, 
    Decimal longitude, 
    int distance
)
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - distance  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[StoreLocation](storelocation-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[StoreLocationController Class](storelocationcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

