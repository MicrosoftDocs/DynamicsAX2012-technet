---
title: IssueLoyaltyCardTransactionServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IssueLoyaltyCardTransactionServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardTransactionServiceRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.issueloyaltycardtransactionservicerequest.issueloyaltycardtransactionservicerequest(v=AX.60)
ms:contentKeyID: 65319054
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardTransactionServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# IssueLoyaltyCardTransactionServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    loyaltyCardNumber As String, _
    loyaltyCardTenderType As LoyaltyCardTenderType, _
    partyRecordId As Long, _
    channelId As Long _
)
'Usage
Dim loyaltyCardNumber As String
Dim loyaltyCardTenderType As LoyaltyCardTenderType
Dim partyRecordId As Long
Dim channelId As Long

Dim instance As New IssueLoyaltyCardTransactionServiceRequest(loyaltyCardNumber, _
    loyaltyCardTenderType, partyRecordId, _
    channelId)
```

``` csharp
public IssueLoyaltyCardTransactionServiceRequest(
    string loyaltyCardNumber,
    LoyaltyCardTenderType loyaltyCardTenderType,
    long partyRecordId,
    long channelId
)
```

``` c++
public:
IssueLoyaltyCardTransactionServiceRequest(
    String^ loyaltyCardNumber, 
    LoyaltyCardTenderType loyaltyCardTenderType, 
    long long partyRecordId, 
    long long channelId
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardTenderType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - partyRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[IssueLoyaltyCardTransactionServiceRequest Class](issueloyaltycardtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

