---
title: GetLoyaltyCardTransactionsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetLoyaltyCardTransactionsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardTransactionsServiceResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.PagedResult{Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardtransactionsserviceresponse.getloyaltycardtransactionsserviceresponse(v=AX.60)
ms:contentKeyID: 65319929
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardTransactionsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactionsServiceResponse Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    loyaltyCardTransactions As PagedResult(Of LoyaltyCardTransaction) _
)
'Usage
Dim loyaltyCardTransactions As PagedResult(Of LoyaltyCardTransaction)

Dim instance As New GetLoyaltyCardTransactionsServiceResponse(loyaltyCardTransactions)
```

``` csharp
public GetLoyaltyCardTransactionsServiceResponse(
    PagedResult<LoyaltyCardTransaction> loyaltyCardTransactions
)
```

``` c++
public:
GetLoyaltyCardTransactionsServiceResponse(
    PagedResult<LoyaltyCardTransaction^>^ loyaltyCardTransactions
)
```

#### Parameters

  - loyaltyCardTransactions  
    Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[LoyaltyCardTransaction](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLoyaltyCardTransactionsServiceResponse Class](getloyaltycardtransactionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

