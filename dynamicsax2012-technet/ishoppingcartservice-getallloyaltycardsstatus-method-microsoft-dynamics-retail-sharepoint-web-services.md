---
title: IShoppingCartService.GetAllLoyaltyCardsStatus Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetAllLoyaltyCardsStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetAllLoyaltyCardsStatus(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice.getallloyaltycardsstatus(v=AX.60)
ms:contentKeyID: 62203015
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetAllLoyaltyCardsStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetAllLoyaltyCardsStatus Method

Gets all loyalty cards with their status

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetAllLoyaltyCardsStatus ( _
    useSecureToken As Boolean _
) As LoyaltyCardsResponse
'Usage
Dim instance As IShoppingCartService
Dim useSecureToken As Boolean
Dim returnValue As LoyaltyCardsResponse

returnValue = instance.GetAllLoyaltyCardsStatus(useSecureToken)
```

``` csharp
[OperationContractAttribute]
LoyaltyCardsResponse GetAllLoyaltyCardsStatus(
    bool useSecureToken
)
```

``` c++
[OperationContractAttribute]
LoyaltyCardsResponse^ GetAllLoyaltyCardsStatus(
    bool useSecureToken
)
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardsResponse](loyaltycardsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A LoyaltyCardsResponse object  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

