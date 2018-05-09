---
title: TransactionServiceClient.GetLoyaltyCardTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetLoyaltyCardTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetLoyaltyCardTransactions(System.String,System.String,System.Int64,System.Int64,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getloyaltycardtransactions(v=AX.60)
ms:contentKeyID: 62202271
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetLoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactions Method

Gets the loyalty card transaction of the given loyalty card and the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetLoyaltyCardTransactions ( _
    loyaltyCardNumber As String, _
    rewardPointId As String, _
    top As Long, _
    skip As Long, _
    calculateRecordCount As Boolean _
) As PagedResult(Of LoyaltyCardTransaction)
'Usage
Dim instance As TransactionServiceClient
Dim loyaltyCardNumber As String
Dim rewardPointId As String
Dim top As Long
Dim skip As Long
Dim calculateRecordCount As Boolean
Dim returnValue As PagedResult(Of LoyaltyCardTransaction)

returnValue = instance.GetLoyaltyCardTransactions(loyaltyCardNumber, _
    rewardPointId, top, skip, calculateRecordCount)
```

``` csharp
public PagedResult<LoyaltyCardTransaction> GetLoyaltyCardTransactions(
    string loyaltyCardNumber,
    string rewardPointId,
    long top,
    long skip,
    bool calculateRecordCount
)
```

``` c++
public:
PagedResult<LoyaltyCardTransaction^>^ GetLoyaltyCardTransactions(
    String^ loyaltyCardNumber, 
    String^ rewardPointId, 
    long long top, 
    long long skip, 
    bool calculateRecordCount
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rewardPointId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - top  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - skip  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - calculateRecordCount  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[LoyaltyCardTransaction](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The page result containing the collection of loyalty card transactions.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

