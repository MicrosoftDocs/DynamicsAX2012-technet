---
title: LoyaltyController.GenerateLoyaltyCardId Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: GenerateLoyaltyCardId Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.GenerateLoyaltyCardId(System.String,Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.loyaltycontroller.generateloyaltycardid(v=AX.60)
ms:contentKeyID: 62202583
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.GenerateLoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# GenerateLoyaltyCardId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Generates loyalty card ID and associates the loyalty card with the current cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GenerateLoyaltyCardId ( _
    shoppingCartId As String, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCart
'Usage
Dim shoppingCartId As String
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCart

returnValue = LoyaltyController.GenerateLoyaltyCardId(shoppingCartId, _
    dataLevel)
```

``` csharp
public static ShoppingCart GenerateLoyaltyCardId(
    string shoppingCartId,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
static ShoppingCart^ GenerateLoyaltyCardId(
    String^ shoppingCartId, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A shopping cart.  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

