---
title: CancelOrderRequest Constructor (String, String, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CancelOrderRequest Constructor (String, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.CancelOrderRequest.#ctor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.cancelorderrequest.cancelorderrequest(v=AX.60)
ms:contentKeyID: 65318661
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CancelOrderRequest Constructor (String, String, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    receiptEmail As String, _
    receiptNumberSequence As String _
)
'Usage
Dim cartId As String
Dim receiptEmail As String
Dim receiptNumberSequence As String

Dim instance As New CancelOrderRequest(cartId, _
    receiptEmail, receiptNumberSequence)
```

``` csharp
public CancelOrderRequest(
    string cartId,
    string receiptEmail,
    string receiptNumberSequence
)
```

``` c++
public:
CancelOrderRequest(
    String^ cartId, 
    String^ receiptEmail, 
    String^ receiptNumberSequence
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptEmail  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptNumberSequence  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CancelOrderRequest Class](cancelorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[CancelOrderRequest Overload](cancelorderrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

