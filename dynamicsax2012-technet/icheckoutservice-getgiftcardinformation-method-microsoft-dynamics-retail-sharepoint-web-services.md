---
title: ICheckoutService.GetGiftCardInformation Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetGiftCardInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetGiftCardInformation(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.getgiftcardinformation(v=AX.60)
ms:contentKeyID: 62204621
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetGiftCardInformation
dev_langs:
- CSharp
- C++
- VB
---

# GetGiftCardInformation Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetGiftCardInformation ( _
    giftCardId As String _
) As GiftCardResponse
'Usage
Dim instance As ICheckoutService
Dim giftCardId As String
Dim returnValue As GiftCardResponse

returnValue = instance.GetGiftCardInformation(giftCardId)
```

``` csharp
[OperationContractAttribute]
GiftCardResponse GetGiftCardInformation(
    string giftCardId
)
```

``` c++
[OperationContractAttribute]
GiftCardResponse^ GetGiftCardInformation(
    String^ giftCardId
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardResponse](giftcardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

