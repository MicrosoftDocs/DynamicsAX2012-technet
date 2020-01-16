---
title: GetLoyaltySchemeLineEarnDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetLoyaltySchemeLineEarnDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineEarnDataRequest.#ctor(System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getloyaltyschemelineearndatarequest.getloyaltyschemelineearndatarequest(v=AX.60)
ms:contentKeyID: 65316922
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineEarnDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltySchemeLineEarnDataRequest Constructor

Initializes a new instance of the [GetLoyaltySchemeLineEarnDataRequest](getloyaltyschemelineearndatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    loyaltyCardNumber As String _
)
'Usage
Dim channelId As Long
Dim loyaltyCardNumber As String

Dim instance As New GetLoyaltySchemeLineEarnDataRequest(channelId, _
    loyaltyCardNumber)
```

``` csharp
public GetLoyaltySchemeLineEarnDataRequest(
    long channelId,
    string loyaltyCardNumber
)
```

``` c++
public:
GetLoyaltySchemeLineEarnDataRequest(
    long long channelId, 
    String^ loyaltyCardNumber
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetLoyaltySchemeLineEarnDataRequest Class](getloyaltyschemelineearndatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

