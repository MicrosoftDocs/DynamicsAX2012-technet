---
title: GetLoyaltyCardTransactionsServiceResponse.LoyaltyCardTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LoyaltyCardTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardTransactionsServiceResponse.LoyaltyCardTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardtransactionsserviceresponse.loyaltycardtransactions(v=AX.60)
ms:contentKeyID: 65321072
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardTransactionsServiceResponse.LoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTransactions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardTransactions As PagedResult(Of LoyaltyCardTransaction)
    Get
    Private Set
'Usage
Dim instance As GetLoyaltyCardTransactionsServiceResponse
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

## See Also

#### Reference

[GetLoyaltyCardTransactionsServiceResponse Class](getloyaltycardtransactionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

