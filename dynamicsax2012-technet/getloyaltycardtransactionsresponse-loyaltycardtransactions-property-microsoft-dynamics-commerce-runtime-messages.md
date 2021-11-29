---
title: GetLoyaltyCardTransactionsResponse.LoyaltyCardTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LoyaltyCardTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardTransactionsResponse.LoyaltyCardTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getloyaltycardtransactionsresponse.loyaltycardtransactions(v=AX.60)
ms:contentKeyID: 62214631
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardTransactionsResponse.LoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTransactions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the loyalty card transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardTransactions As PagedResult(Of LoyaltyCardTransaction)
    Get
    Private Set
'Usage
Dim instance As GetLoyaltyCardTransactionsResponse
Dim value As PagedResult(Of LoyaltyCardTransaction)

value = instance.LoyaltyCardTransactions
```

``` csharp
[DataMemberAttribute]
public PagedResult<LoyaltyCardTransaction> LoyaltyCardTransactions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PagedResult<LoyaltyCardTransaction^>^ LoyaltyCardTransactions {
    PagedResult<LoyaltyCardTransaction^>^ get ();
    private: void set (PagedResult<LoyaltyCardTransaction^>^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[LoyaltyCardTransaction](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [PagedResult\<TEntity\>](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[GetLoyaltyCardTransactionsResponse Class](getloyaltycardtransactionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

