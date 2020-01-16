---
title: LoyaltyCardTransactionsResponse.LoyaltyCardTransactions Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: LoyaltyCardTransactions Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardTransactionsResponse.LoyaltyCardTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.loyaltycardtransactionsresponse.loyaltycardtransactions(v=AX.60)
ms:contentKeyID: 65315574
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardTransactionsResponse.LoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTransactions Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardTransactions As ReadOnlyCollection(Of LoyaltyCardTransaction)
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransactionsResponse
Dim value As ReadOnlyCollection(Of LoyaltyCardTransaction)

value = instance.LoyaltyCardTransactions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<LoyaltyCardTransaction> LoyaltyCardTransactions { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<LoyaltyCardTransaction^>^ LoyaltyCardTransactions {
    ReadOnlyCollection<LoyaltyCardTransaction^>^ get ();
    internal: void set (ReadOnlyCollection<LoyaltyCardTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LoyaltyCardTransaction](loyaltycardtransaction-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LoyaltyCardTransactionsResponse Class](loyaltycardtransactionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

