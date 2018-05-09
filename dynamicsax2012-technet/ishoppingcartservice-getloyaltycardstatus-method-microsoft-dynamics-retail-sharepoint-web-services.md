---
title: IShoppingCartService.GetLoyaltyCardStatus Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetLoyaltyCardStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetLoyaltyCardStatus(System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice.getloyaltycardstatus(v=AX.60)
ms:contentKeyID: 62207326
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetLoyaltyCardStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardStatus Method

Gets a loyalty card status given a loyalty card id.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetLoyaltyCardStatus ( _
    useSecureToken As Boolean, _
    loyaltyCardNumber As String _
) As LoyaltyCardResponse
'Usage
Dim instance As IShoppingCartService
Dim useSecureToken As Boolean
Dim loyaltyCardNumber As String
Dim returnValue As LoyaltyCardResponse

returnValue = instance.GetLoyaltyCardStatus(useSecureToken, _
    loyaltyCardNumber)
```

``` csharp
[OperationContractAttribute]
LoyaltyCardResponse GetLoyaltyCardStatus(
    bool useSecureToken,
    string loyaltyCardNumber
)
```

``` c++
[OperationContractAttribute]
LoyaltyCardResponse^ GetLoyaltyCardStatus(
    bool useSecureToken, 
    String^ loyaltyCardNumber
)
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardResponse](loyaltycardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A LoyaltyCardResponse object  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

