---
title: LoyaltyServiceBase.GetLoyaltyCardTransactions Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetLoyaltyCardTransactions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase.GetLoyaltyCardTransactions(System.String,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.loyaltyservicebase.getloyaltycardtransactions(v=AX.60)
ms:contentKeyID: 65315587
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase.GetLoyaltyCardTransactions
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
Public Overridable Function GetLoyaltyCardTransactions ( _
    loyaltyCardNumber As String, _
    rewardPointId As String, _
    topRows As Integer _
) As LoyaltyCardTransactionsResponse
'Usage
Dim instance As LoyaltyServiceBase
Dim loyaltyCardNumber As String
Dim rewardPointId As String
Dim topRows As Integer
Dim returnValue As LoyaltyCardTransactionsResponse

returnValue = instance.GetLoyaltyCardTransactions(loyaltyCardNumber, _
    rewardPointId, topRows)
```

``` csharp
public virtual LoyaltyCardTransactionsResponse GetLoyaltyCardTransactions(
    string loyaltyCardNumber,
    string rewardPointId,
    int topRows
)
```

``` c++
public:
virtual LoyaltyCardTransactionsResponse^ GetLoyaltyCardTransactions(
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

#### Implements

[ILoyaltyService.GetLoyaltyCardTransactions(String, String, Int32)](iloyaltyservice-getloyaltycardtransactions-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[LoyaltyServiceBase Class](loyaltyservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

