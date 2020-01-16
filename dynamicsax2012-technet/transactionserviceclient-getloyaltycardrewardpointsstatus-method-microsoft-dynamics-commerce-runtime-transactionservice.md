---
title: TransactionServiceClient.GetLoyaltyCardRewardPointsStatus Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetLoyaltyCardRewardPointsStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetLoyaltyCardRewardPointsStatus(System.DateTime,System.String,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getloyaltycardrewardpointsstatus(v=AX.60)
ms:contentKeyID: 62214614
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetLoyaltyCardRewardPointsStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardRewardPointsStatus Method

Gets the status of the loyalty reward points by card number or directory party record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetLoyaltyCardRewardPointsStatus ( _
    channelLocalDate As DateTime, _
    loyaltyCardNumber As String, _
    excludeBlocked As Boolean, _
    excludeNoTender As Boolean, _
    includeRelatedCardsForContactTender As Boolean, _
    includeNonRedeemablePoints As Boolean, _
    includeActivePointsOnly As Boolean, _
    locale As String _
) As Collection(Of LoyaltyCard)
'Usage
Dim instance As TransactionServiceClient
Dim channelLocalDate As DateTime
Dim loyaltyCardNumber As String
Dim excludeBlocked As Boolean
Dim excludeNoTender As Boolean
Dim includeRelatedCardsForContactTender As Boolean
Dim includeNonRedeemablePoints As Boolean
Dim includeActivePointsOnly As Boolean
Dim locale As String
Dim returnValue As Collection(Of LoyaltyCard)

returnValue = instance.GetLoyaltyCardRewardPointsStatus(channelLocalDate, _
    loyaltyCardNumber, excludeBlocked, _
    excludeNoTender, includeRelatedCardsForContactTender, _
    includeNonRedeemablePoints, includeActivePointsOnly, _
    locale)
```

``` csharp
public Collection<LoyaltyCard> GetLoyaltyCardRewardPointsStatus(
    DateTime channelLocalDate,
    string loyaltyCardNumber,
    bool excludeBlocked,
    bool excludeNoTender,
    bool includeRelatedCardsForContactTender,
    bool includeNonRedeemablePoints,
    bool includeActivePointsOnly,
    string locale
)
```

``` c++
public:
Collection<LoyaltyCard^>^ GetLoyaltyCardRewardPointsStatus(
    DateTime channelLocalDate, 
    String^ loyaltyCardNumber, 
    bool excludeBlocked, 
    bool excludeNoTender, 
    bool includeRelatedCardsForContactTender, 
    bool includeNonRedeemablePoints, 
    bool includeActivePointsOnly, 
    String^ locale
)
```

#### Parameters

  - channelLocalDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - excludeBlocked  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - excludeNoTender  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - includeRelatedCardsForContactTender  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - includeNonRedeemablePoints  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - includeActivePointsOnly  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The loyalty point status per loyalty card.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

