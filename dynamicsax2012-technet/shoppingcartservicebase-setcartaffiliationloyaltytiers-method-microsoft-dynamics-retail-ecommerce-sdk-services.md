---
title: ShoppingCartServiceBase.SetCartAffiliationLoyaltyTiers Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SetCartAffiliationLoyaltyTiers Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.SetCartAffiliationLoyaltyTiers(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartservicebase.setcartaffiliationloyaltytiers(v=AX.60)
ms:contentKeyID: 65317183
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.SetCartAffiliationLoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# SetCartAffiliationLoyaltyTiers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Function SetCartAffiliationLoyaltyTiers ( _
    tiers As IEnumerable(Of Long) _
) As NullResponse
'Usage
Dim instance As ShoppingCartServiceBase
Dim tiers As IEnumerable(Of Long)
Dim returnValue As NullResponse

returnValue = instance.SetCartAffiliationLoyaltyTiers(tiers)
```

``` csharp
public NullResponse SetCartAffiliationLoyaltyTiers(
    IEnumerable<long> tiers
)
```

``` c++
public:
virtual NullResponse^ SetCartAffiliationLoyaltyTiers(
    IEnumerable<long long>^ tiers
) sealed
```

#### Parameters

  - tiers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.NullResponse](nullresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IShoppingCartService.SetCartAffiliationLoyaltyTiers(IEnumerable\<Int64\>)](ishoppingcartservice-setcartaffiliationloyaltytiers-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ShoppingCartServiceBase Class](shoppingcartservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

