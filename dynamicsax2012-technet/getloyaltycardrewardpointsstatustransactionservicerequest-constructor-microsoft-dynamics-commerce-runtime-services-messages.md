---
title: GetLoyaltyCardRewardPointsStatusTransactionServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetLoyaltyCardRewardPointsStatusTransactionServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceRequest.#ctor(System.DateTime,System.String,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardrewardpointsstatustransactionservicerequest.getloyaltycardrewardpointsstatustransactionservicerequest(v=AX.60)
ms:contentKeyID: 65320924
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardRewardPointsStatusTransactionServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelLocalDate As DateTime, _
    loyaltyCardNumber As String, _
    excludeBlocked As Boolean, _
    excludeNoTender As Boolean, _
    includeRelatedCardsForContactTender As Boolean, _
    includeNonRedeemablePoints As Boolean, _
    includeActivePointsOnly As Boolean, _
    locale As String _
)
'Usage
Dim channelLocalDate As DateTime
Dim loyaltyCardNumber As String
Dim excludeBlocked As Boolean
Dim excludeNoTender As Boolean
Dim includeRelatedCardsForContactTender As Boolean
Dim includeNonRedeemablePoints As Boolean
Dim includeActivePointsOnly As Boolean
Dim locale As String

Dim instance As New GetLoyaltyCardRewardPointsStatusTransactionServiceRequest(channelLocalDate, _
    loyaltyCardNumber, excludeBlocked, _
    excludeNoTender, includeRelatedCardsForContactTender, _
    includeNonRedeemablePoints, includeActivePointsOnly, _
    locale)
```

``` csharp
public GetLoyaltyCardRewardPointsStatusTransactionServiceRequest(
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
GetLoyaltyCardRewardPointsStatusTransactionServiceRequest(
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

## See Also

#### Reference

[GetLoyaltyCardRewardPointsStatusTransactionServiceRequest Class](getloyaltycardrewardpointsstatustransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

