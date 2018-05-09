---
title: PickupAtStoreRequest Constructor (String, String, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PickupAtStoreRequest Constructor (String, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.PickupAtStoreRequest.#ctor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.pickupatstorerequest.pickupatstorerequest(v=AX.60)
ms:contentKeyID: 65316250
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PickupAtStoreRequest Constructor (String, String, String)

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

Dim instance As New PickupAtStoreRequest(cartId, _
    receiptEmail, receiptNumberSequence)
```

``` csharp
public PickupAtStoreRequest(
    string cartId,
    string receiptEmail,
    string receiptNumberSequence
)
```

``` c++
public:
PickupAtStoreRequest(
    String^ cartId, 
    String^ receiptEmail, 
    String^ receiptNumberSequence
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptEmail  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptNumberSequence  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[PickupAtStoreRequest Class](pickupatstorerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[PickupAtStoreRequest Overload](pickupatstorerequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

