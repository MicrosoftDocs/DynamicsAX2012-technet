---
title: GiftCardRealtimeRequestBase Constructor (String, Int64, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GiftCardRealtimeRequestBase Constructor (String, Int64, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GiftCardRealtimeRequestBase.#ctor(System.String,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.giftcardrealtimerequestbase.giftcardrealtimerequestbase(v=AX.60)
ms:contentKeyID: 65320678
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GiftCardRealtimeRequestBase Constructor (String, Int64, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    cardId As String, _
    channelId As Long, _
    terminalId As String _
)
'Usage
Dim cardId As String
Dim channelId As Long
Dim terminalId As String

Dim instance As New GiftCardRealtimeRequestBase(cardId, _
    channelId, terminalId)
```

``` csharp
protected GiftCardRealtimeRequestBase(
    string cardId,
    long channelId,
    string terminalId
)
```

``` c++
protected:
GiftCardRealtimeRequestBase(
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

[GiftCardRealtimeRequestBase Class](giftcardrealtimerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GiftCardRealtimeRequestBase Overload](giftcardrealtimerequestbase-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

