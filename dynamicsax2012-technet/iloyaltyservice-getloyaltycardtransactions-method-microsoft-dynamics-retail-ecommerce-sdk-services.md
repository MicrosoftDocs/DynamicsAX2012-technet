---
title: ILoyaltyService.GetLoyaltyCardTransactions Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetLoyaltyCardTransactions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ILoyaltyService.GetLoyaltyCardTransactions(System.String,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.iloyaltyservice.getloyaltycardtransactions(v=AX.60)
ms:contentKeyID: 65318049
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ILoyaltyService.GetLoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetLoyaltyCardTransactions ( _
    loyaltyCardNumber As String, _
    rewardPointId As String, _
    topRows As Integer _
) As LoyaltyCardTransactionsResponse
'Usage
Dim instance As ILoyaltyService
Dim loyaltyCardNumber As String
Dim rewardPointId As String
Dim topRows As Integer
Dim returnValue As LoyaltyCardTransactionsResponse

returnValue = instance.GetLoyaltyCardTransactions(loyaltyCardNumber, _
    rewardPointId, topRows)
```

``` csharp
[OperationContractAttribute]
LoyaltyCardTransactionsResponse GetLoyaltyCardTransactions(
    string loyaltyCardNumber,
    string rewardPointId,
    int topRows
)
```

``` c++
[OperationContractAttribute]
LoyaltyCardTransactionsResponse^ GetLoyaltyCardTransactions(
    String^ loyaltyCardNumber, 
    String^ rewardPointId, 
    int topRows
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rewardPointId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - topRows  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardTransactionsResponse](loyaltycardtransactionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ILoyaltyService Interface](iloyaltyservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

