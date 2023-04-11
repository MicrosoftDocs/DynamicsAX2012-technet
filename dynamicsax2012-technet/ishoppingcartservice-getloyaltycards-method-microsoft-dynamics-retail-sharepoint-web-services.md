---
title: IShoppingCartService.GetLoyaltyCards Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetLoyaltyCards Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetLoyaltyCards(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice.getloyaltycards(v=AX.60)
ms:contentKeyID: 62206683
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetLoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCards Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a read only collection of all Loyalty Cards for the customer

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetLoyaltyCards ( _
    useSecureToken As Boolean _
) As LoyaltyCardsResponse
'Usage
Dim instance As IShoppingCartService
Dim useSecureToken As Boolean
Dim returnValue As LoyaltyCardsResponse

returnValue = instance.GetLoyaltyCards(useSecureToken)
```

``` csharp
[OperationContractAttribute]
LoyaltyCardsResponse GetLoyaltyCards(
    bool useSecureToken
)
```

``` c++
[OperationContractAttribute]
LoyaltyCardsResponse^ GetLoyaltyCards(
    bool useSecureToken
)
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardsResponse](loyaltycardsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A LoyaltyCardsResponse object  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

