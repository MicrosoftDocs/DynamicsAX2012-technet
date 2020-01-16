---
title: GetDeliveryOptionsRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetDeliveryOptionsRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdeliveryoptionsrequest.getdeliveryoptionsrequest(v=AX.60)
ms:contentKeyID: 62205294
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDeliveryOptionsRequest Constructor (String, String)

Initializes a new instance of the [GetDeliveryOptionsRequest](getdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

Creates request for order level delivery modes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    customerAccountNumber As String _
)
'Usage
Dim cartId As String
Dim customerAccountNumber As String

Dim instance As New GetDeliveryOptionsRequest(cartId, _
    customerAccountNumber)
```

``` csharp
public GetDeliveryOptionsRequest(
    string cartId,
    string customerAccountNumber
)
```

``` c++
public:
GetDeliveryOptionsRequest(
    String^ cartId, 
    String^ customerAccountNumber
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetDeliveryOptionsRequest Class](getdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetDeliveryOptionsRequest Overload](getdeliveryoptionsrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

