---
title: ShoppingCartService.GetLoyaltyCardStatus Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetLoyaltyCardStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetLoyaltyCardStatus(System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice.getloyaltycardstatus(v=AX.60)
ms:contentKeyID: 62205032
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetLoyaltyCardStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the status of a loyalty card given it's id

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetLoyaltyCardStatus ( _
    useSecureToken As Boolean, _
    loyaltyCardNumber As String _
) As LoyaltyCardResponse
'Usage
Dim instance As ShoppingCartService
Dim useSecureToken As Boolean
Dim loyaltyCardNumber As String
Dim returnValue As LoyaltyCardResponse

returnValue = instance.GetLoyaltyCardStatus(useSecureToken, _
    loyaltyCardNumber)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public LoyaltyCardResponse GetLoyaltyCardStatus(
    bool useSecureToken,
    string loyaltyCardNumber
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual LoyaltyCardResponse^ GetLoyaltyCardStatus(
    bool useSecureToken, 
    String^ loyaltyCardNumber
) sealed
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardResponse](loyaltycardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A loyaltyCardResponse object  

#### Implements

[IShoppingCartService.GetLoyaltyCardStatus(Boolean, String)](ishoppingcartservice-getloyaltycardstatus-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

