---
title: SaveVoidTransactionRequest Constructor (String, IEnumerable(ReasonCodeLine)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SaveVoidTransactionRequest Constructor (String, IEnumerable(ReasonCodeLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveVoidTransactionRequest.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savevoidtransactionrequest.savevoidtransactionrequest(v=AX.60)
ms:contentKeyID: 62211584
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveVoidTransactionRequest Constructor (String, IEnumerable(ReasonCodeLine))

Initializes a new instance of the [SaveVoidTransactionRequest](savevoidtransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    reasonCodeLines As IEnumerable(Of ReasonCodeLine) _
)
'Usage
Dim cartId As String
Dim reasonCodeLines As IEnumerable(Of ReasonCodeLine)

Dim instance As New SaveVoidTransactionRequest(cartId, _
    reasonCodeLines)
```

``` csharp
public SaveVoidTransactionRequest(
    string cartId,
    IEnumerable<ReasonCodeLine> reasonCodeLines
)
```

``` c++
public:
SaveVoidTransactionRequest(
    String^ cartId, 
    IEnumerable<ReasonCodeLine^>^ reasonCodeLines
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reasonCodeLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SaveVoidTransactionRequest Class](savevoidtransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SaveVoidTransactionRequest Overload](savevoidtransactionrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

