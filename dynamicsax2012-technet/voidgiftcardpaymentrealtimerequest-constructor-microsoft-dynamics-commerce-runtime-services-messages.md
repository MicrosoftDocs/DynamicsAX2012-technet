---
title: VoidGiftCardPaymentRealtimeRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: VoidGiftCardPaymentRealtimeRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidGiftCardPaymentRealtimeRequest.#ctor(System.String,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.voidgiftcardpaymentrealtimerequest.voidgiftcardpaymentrealtimerequest(v=AX.60)
ms:contentKeyID: 65322446
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidGiftCardPaymentRealtimeRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# VoidGiftCardPaymentRealtimeRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cardId As String, _
    channelId As Long, _
    terminalId As String _
)
'Usage
Dim cardId As String
Dim channelId As Long
Dim terminalId As String

Dim instance As New VoidGiftCardPaymentRealtimeRequest(cardId, _
    channelId, terminalId)
```

``` csharp
public VoidGiftCardPaymentRealtimeRequest(
    string cardId,
    long channelId,
    string terminalId
)
```

``` c++
public:
VoidGiftCardPaymentRealtimeRequest(
    String^ cardId, 
    long long channelId, 
    String^ terminalId
)
```

#### Parameters

  - cardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[VoidGiftCardPaymentRealtimeRequest Class](voidgiftcardpaymentrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

