---
title: GetLoyaltyCardTransactionsResponse Constructor (PagedResult(LoyaltyCardTransaction)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetLoyaltyCardTransactionsResponse Constructor (PagedResult(LoyaltyCardTransaction))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardTransactionsResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.PagedResult{Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getloyaltycardtransactionsresponse.getloyaltycardtransactionsresponse(v=AX.60)
ms:contentKeyID: 62214737
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetLoyaltyCardTransactionsResponse Constructor (PagedResult(LoyaltyCardTransaction))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetLoyaltyCardTransactionsResponse](getloyaltycardtransactionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    loyaltyCardTransactions As PagedResult(Of LoyaltyCardTransaction) _
)
'Usage
Dim loyaltyCardTransactions As PagedResult(Of LoyaltyCardTransaction)

Dim instance As New GetLoyaltyCardTransactionsResponse(loyaltyCardTransactions)
```

``` csharp
public GetLoyaltyCardTransactionsResponse(
    PagedResult<LoyaltyCardTransaction> loyaltyCardTransactions
)
```

``` c++
public:
GetLoyaltyCardTransactionsResponse(
    PagedResult<LoyaltyCardTransaction^>^ loyaltyCardTransactions
)
```

#### Parameters

  - loyaltyCardTransactions  
    Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[LoyaltyCardTransaction](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLoyaltyCardTransactionsResponse Class](getloyaltycardtransactionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetLoyaltyCardTransactionsResponse Overload](getloyaltycardtransactionsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

