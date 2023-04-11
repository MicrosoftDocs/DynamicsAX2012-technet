---
title: IShoppingCartService.UpdateLoyaltyCardId Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: UpdateLoyaltyCardId Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.UpdateLoyaltyCardId(System.Boolean,System.String,Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice.updateloyaltycardid(v=AX.60)
ms:contentKeyID: 62206173
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.UpdateLoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# UpdateLoyaltyCardId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the loyalty card id on the shopping cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function UpdateLoyaltyCardId ( _
    useSecureToken As Boolean, _
    loyaltyCardId As String, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As IShoppingCartService
Dim useSecureToken As Boolean
Dim loyaltyCardId As String
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.UpdateLoyaltyCardId(useSecureToken, _
    loyaltyCardId, dataLevel)
```

``` csharp
[OperationContractAttribute]
ShoppingCartResponse UpdateLoyaltyCardId(
    bool useSecureToken,
    string loyaltyCardId,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
[OperationContractAttribute]
ShoppingCartResponse^ UpdateLoyaltyCardId(
    bool useSecureToken, 
    String^ loyaltyCardId, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The shopping cart.  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

