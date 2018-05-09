---
title: TransactionServiceClient.IssueLoyaltyCard Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: IssueLoyaltyCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.IssueLoyaltyCard(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.issueloyaltycard(v=AX.60)
ms:contentKeyID: 62207813
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.IssueLoyaltyCard
dev_langs:
- CSharp
- C++
- VB
---

# IssueLoyaltyCard Method

Issues a new loyalty card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function IssueLoyaltyCard ( _
    loyaltyCardNumber As String, _
    cardTenderType As LoyaltyCardTenderType, _
    partyRecordId As Long, _
    channelRecordId As Long _
) As LoyaltyCard
'Usage
Dim instance As TransactionServiceClient
Dim loyaltyCardNumber As String
Dim cardTenderType As LoyaltyCardTenderType
Dim partyRecordId As Long
Dim channelRecordId As Long
Dim returnValue As LoyaltyCard

returnValue = instance.IssueLoyaltyCard(loyaltyCardNumber, _
    cardTenderType, partyRecordId, channelRecordId)
```

``` csharp
public LoyaltyCard IssueLoyaltyCard(
    string loyaltyCardNumber,
    LoyaltyCardTenderType cardTenderType,
    long partyRecordId,
    long channelRecordId
)
```

``` c++
public:
LoyaltyCard^ IssueLoyaltyCard(
    String^ loyaltyCardNumber, 
    LoyaltyCardTenderType cardTenderType, 
    long long partyRecordId, 
    long long channelRecordId
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cardTenderType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - partyRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - channelRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The created loyalty card.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

