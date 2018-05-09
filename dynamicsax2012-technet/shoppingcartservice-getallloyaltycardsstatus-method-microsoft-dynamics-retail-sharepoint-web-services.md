---
title: ShoppingCartService.GetAllLoyaltyCardsStatus Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetAllLoyaltyCardsStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetAllLoyaltyCardsStatus(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice.getallloyaltycardsstatus(v=AX.60)
ms:contentKeyID: 62202561
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetAllLoyaltyCardsStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetAllLoyaltyCardsStatus Method

Gets a read only collection of all loyalty card with their status

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetAllLoyaltyCardsStatus ( _
    useSecureToken As Boolean _
) As LoyaltyCardsResponse
'Usage
Dim instance As ShoppingCartService
Dim useSecureToken As Boolean
Dim returnValue As LoyaltyCardsResponse

returnValue = instance.GetAllLoyaltyCardsStatus(useSecureToken)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public LoyaltyCardsResponse GetAllLoyaltyCardsStatus(
    bool useSecureToken
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual LoyaltyCardsResponse^ GetAllLoyaltyCardsStatus(
    bool useSecureToken
) sealed
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardsResponse](loyaltycardsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A loyaltyCardsResponse object  

#### Implements

[IShoppingCartService.GetAllLoyaltyCardsStatus(Boolean)](ishoppingcartservice-getallloyaltycardsstatus-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

