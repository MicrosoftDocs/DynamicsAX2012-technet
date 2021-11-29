---
title: ShoppingCartServiceBase.AddItems Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: AddItems Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.AddItems(System.Boolean,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Listing},Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartservicebase.additems(v=AX.60)
ms:contentKeyID: 65318456
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.AddItems
dev_langs:
- CSharp
- C++
- VB
---

# AddItems Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function AddItems ( _
    isCheckoutSession As Boolean, _
    listings As IEnumerable(Of Listing), _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As ShoppingCartServiceBase
Dim isCheckoutSession As Boolean
Dim listings As IEnumerable(Of Listing)
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.AddItems(isCheckoutSession, _
    listings, dataLevel)
```

``` csharp
public virtual ShoppingCartResponse AddItems(
    bool isCheckoutSession,
    IEnumerable<Listing> listings,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
virtual ShoppingCartResponse^ AddItems(
    bool isCheckoutSession, 
    IEnumerable<Listing^>^ listings, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - isCheckoutSession  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - listings  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IShoppingCartService.AddItems(Boolean, IEnumerable\<Listing\>, ShoppingCartDataLevel)](ishoppingcartservice-additems-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ShoppingCartServiceBase Class](shoppingcartservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

