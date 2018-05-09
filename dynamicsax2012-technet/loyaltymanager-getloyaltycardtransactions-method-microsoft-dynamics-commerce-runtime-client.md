---
title: LoyaltyManager.GetLoyaltyCardTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLoyaltyCardTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.GetLoyaltyCardTransactions(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.loyaltymanager.getloyaltycardtransactions(v=AX.60)
ms:contentKeyID: 65322915
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.GetLoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactions Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLoyaltyCardTransactions ( _
    loyaltyCardNumber As String, _
    rewardPointId As String, _
    settings As QueryResultSettings _
) As PagedResult(Of LoyaltyCardTransaction)
'Usage
Dim instance As LoyaltyManager
Dim loyaltyCardNumber As String
Dim rewardPointId As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of LoyaltyCardTransaction)

returnValue = instance.GetLoyaltyCardTransactions(loyaltyCardNumber, _
    rewardPointId, settings)
```

``` csharp
public PagedResult<LoyaltyCardTransaction> GetLoyaltyCardTransactions(
    string loyaltyCardNumber,
    string rewardPointId,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<LoyaltyCardTransaction^>^ GetLoyaltyCardTransactions(
    String^ loyaltyCardNumber, 
    String^ rewardPointId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rewardPointId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[LoyaltyCardTransaction](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[LoyaltyManager Class](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

