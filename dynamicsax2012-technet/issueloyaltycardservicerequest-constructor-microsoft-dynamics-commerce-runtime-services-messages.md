---
title: IssueLoyaltyCardServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IssueLoyaltyCardServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardServiceRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType,System.String,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.issueloyaltycardservicerequest.issueloyaltycardservicerequest(v=AX.60)
ms:contentKeyID: 65319944
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# IssueLoyaltyCardServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    loyaltyCardNumber As String, _
    loyaltyCardTenderType As LoyaltyCardTenderType, _
    customerAccount As String, _
    partyRecordId As Long, _
    channelId As Long _
)
'Usage
Dim loyaltyCardNumber As String
Dim loyaltyCardTenderType As LoyaltyCardTenderType
Dim customerAccount As String
Dim partyRecordId As Long
Dim channelId As Long

Dim instance As New IssueLoyaltyCardServiceRequest(loyaltyCardNumber, _
    loyaltyCardTenderType, customerAccount, _
    partyRecordId, channelId)
```

``` csharp
public IssueLoyaltyCardServiceRequest(
    string loyaltyCardNumber,
    LoyaltyCardTenderType loyaltyCardTenderType,
    string customerAccount,
    long partyRecordId,
    long channelId
)
```

``` c++
public:
IssueLoyaltyCardServiceRequest(
    String^ loyaltyCardNumber, 
    LoyaltyCardTenderType loyaltyCardTenderType, 
    String^ customerAccount, 
    long long partyRecordId, 
    long long channelId
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardTenderType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - partyRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[IssueLoyaltyCardServiceRequest Class](issueloyaltycardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

