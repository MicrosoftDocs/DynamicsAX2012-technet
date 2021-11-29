---
title: CheckoutService.GetGiftCardInformation Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetGiftCardInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetGiftCardInformation(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.getgiftcardinformation(v=AX.60)
ms:contentKeyID: 62205424
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetGiftCardInformation
dev_langs:
- CSharp
- C++
- VB
---

# GetGiftCardInformation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the gift card balance.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetGiftCardInformation ( _
    giftCardId As String _
) As GiftCardResponse
'Usage
Dim instance As CheckoutService
Dim giftCardId As String
Dim returnValue As GiftCardResponse

returnValue = instance.GetGiftCardInformation(giftCardId)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public GiftCardResponse GetGiftCardInformation(
    string giftCardId
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual GiftCardResponse^ GetGiftCardInformation(
    String^ giftCardId
) sealed
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardResponse](giftcardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The gift card balance response.  

#### Implements

[ICheckoutService.GetGiftCardInformation(String)](icheckoutservice-getgiftcardinformation-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

