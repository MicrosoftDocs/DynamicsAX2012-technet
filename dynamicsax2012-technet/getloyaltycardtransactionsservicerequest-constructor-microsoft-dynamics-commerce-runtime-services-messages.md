---
title: GetLoyaltyCardTransactionsServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetLoyaltyCardTransactionsServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardTransactionsServiceRequest.#ctor(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardtransactionsservicerequest.getloyaltycardtransactionsservicerequest(v=AX.60)
ms:contentKeyID: 65320059
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardTransactionsServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactionsServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cardNumber As String, _
    rewardPointId As String, _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim cardNumber As String
Dim rewardPointId As String
Dim queryResultSettings As QueryResultSettings

Dim instance As New GetLoyaltyCardTransactionsServiceRequest(cardNumber, _
    rewardPointId, queryResultSettings)
```

``` csharp
public GetLoyaltyCardTransactionsServiceRequest(
    string cardNumber,
    string rewardPointId,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
GetLoyaltyCardTransactionsServiceRequest(
    String^ cardNumber, 
    String^ rewardPointId, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rewardPointId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetLoyaltyCardTransactionsServiceRequest Class](getloyaltycardtransactionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

