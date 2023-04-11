---
title: GetLoyaltySchemeLineRedeemDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetLoyaltySchemeLineRedeemDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineRedeemDataRequest.#ctor(System.Int64,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getloyaltyschemelineredeemdatarequest.getloyaltyschemelineredeemdatarequest(v=AX.60)
ms:contentKeyID: 65320950
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineRedeemDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltySchemeLineRedeemDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetLoyaltySchemeLineRedeemDataRequest](getloyaltyschemelineredeemdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    loyaltyCardNumber As String, _
    loyaltyRewardPointId As String _
)
'Usage
Dim channelId As Long
Dim loyaltyCardNumber As String
Dim loyaltyRewardPointId As String

Dim instance As New GetLoyaltySchemeLineRedeemDataRequest(channelId, _
    loyaltyCardNumber, loyaltyRewardPointId)
```

``` csharp
public GetLoyaltySchemeLineRedeemDataRequest(
    long channelId,
    string loyaltyCardNumber,
    string loyaltyRewardPointId
)
```

``` c++
public:
GetLoyaltySchemeLineRedeemDataRequest(
    long long channelId, 
    String^ loyaltyCardNumber, 
    String^ loyaltyRewardPointId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - loyaltyRewardPointId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetLoyaltySchemeLineRedeemDataRequest Class](getloyaltyschemelineredeemdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

