---
title: IShoppingCartService.GetLoyaltyCardTransactions Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetLoyaltyCardTransactions Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetLoyaltyCardTransactions(System.Boolean,System.String,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice.getloyaltycardtransactions(v=AX.60)
ms:contentKeyID: 62205420
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetLoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactions Method

Gets all loyalty card transaction data

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetLoyaltyCardTransactions ( _
    useSecureToken As Boolean, _
    loyaltyCardNumber As String, _
    rewardPointId As String, _
    topRows As Integer _
) As LoyaltyCardTransactionsResponse
'Usage
Dim instance As IShoppingCartService
Dim useSecureToken As Boolean
Dim loyaltyCardNumber As String
Dim rewardPointId As String
Dim topRows As Integer
Dim returnValue As LoyaltyCardTransactionsResponse

returnValue = instance.GetLoyaltyCardTransactions(useSecureToken, _
    loyaltyCardNumber, rewardPointId, _
    topRows)
```

``` csharp
[OperationContractAttribute]
LoyaltyCardTransactionsResponse GetLoyaltyCardTransactions(
    bool useSecureToken,
    string loyaltyCardNumber,
    string rewardPointId,
    int topRows
)
```

``` c++
[OperationContractAttribute]
LoyaltyCardTransactionsResponse^ GetLoyaltyCardTransactions(
    bool useSecureToken, 
    String^ loyaltyCardNumber, 
    String^ rewardPointId, 
    int topRows
)
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rewardPointId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - topRows  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransactionsResponse](loyaltycardtransactionsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A LoyaltyCardTransactionsResponse object  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

