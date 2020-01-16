---
title: IShoppingCartService.GetShoppingCarts Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetShoppingCarts Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetShoppingCarts(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice.getshoppingcarts(v=AX.60)
ms:contentKeyID: 62203315
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetShoppingCarts
dev_langs:
- CSharp
- C++
- VB
---

# GetShoppingCarts Method

Gets all shopping carts associated with the current user.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetShoppingCarts ( _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartCollectionResponse
'Usage
Dim instance As IShoppingCartService
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartCollectionResponse

returnValue = instance.GetShoppingCarts(dataLevel)
```

``` csharp
[OperationContractAttribute]
ShoppingCartCollectionResponse GetShoppingCarts(
    ShoppingCartDataLevel dataLevel
)
```

``` c++
[OperationContractAttribute]
ShoppingCartCollectionResponse^ GetShoppingCarts(
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartCollectionResponse](shoppingcartcollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the list of shopping carts.  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

