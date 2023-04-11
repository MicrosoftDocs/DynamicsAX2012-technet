---
title: ShoppingCartServiceBase.AddOrRemovePromotionCode Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: AddOrRemovePromotionCode Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.AddOrRemovePromotionCode(System.Boolean,System.String,System.Boolean,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartservicebase.addorremovepromotioncode(v=AX.60)
ms:contentKeyID: 65316030
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.AddOrRemovePromotionCode
dev_langs:
- CSharp
- C++
- VB
---

# AddOrRemovePromotionCode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function AddOrRemovePromotionCode ( _
    isCheckoutSession As Boolean, _
    promotionCode As String, _
    isAdd As Boolean, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As ShoppingCartServiceBase
Dim isCheckoutSession As Boolean
Dim promotionCode As String
Dim isAdd As Boolean
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.AddOrRemovePromotionCode(isCheckoutSession, _
    promotionCode, isAdd, dataLevel)
```

``` csharp
public virtual ShoppingCartResponse AddOrRemovePromotionCode(
    bool isCheckoutSession,
    string promotionCode,
    bool isAdd,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
virtual ShoppingCartResponse^ AddOrRemovePromotionCode(
    bool isCheckoutSession, 
    String^ promotionCode, 
    bool isAdd, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - isCheckoutSession  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - promotionCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isAdd  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IShoppingCartService.AddOrRemovePromotionCode(Boolean, String, Boolean, ShoppingCartDataLevel)](ishoppingcartservice-addorremovepromotioncode-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ShoppingCartServiceBase Class](shoppingcartservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

