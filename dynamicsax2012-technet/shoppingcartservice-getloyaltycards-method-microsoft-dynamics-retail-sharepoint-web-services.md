---
title: ShoppingCartService.GetLoyaltyCards Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetLoyaltyCards Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetLoyaltyCards(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice.getloyaltycards(v=AX.60)
ms:contentKeyID: 62206958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetLoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCards Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a read only collection of all loyalty card numbers

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetLoyaltyCards ( _
    useSecureToken As Boolean _
) As LoyaltyCardsResponse
'Usage
Dim instance As ShoppingCartService
Dim useSecureToken As Boolean
Dim returnValue As LoyaltyCardsResponse

returnValue = instance.GetLoyaltyCards(useSecureToken)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public LoyaltyCardsResponse GetLoyaltyCards(
    bool useSecureToken
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual LoyaltyCardsResponse^ GetLoyaltyCards(
    bool useSecureToken
) sealed
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardsResponse](loyaltycardsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A loyaltyCardsResponse object  

#### Implements

[IShoppingCartService.GetLoyaltyCards(Boolean)](ishoppingcartservice-getloyaltycards-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

