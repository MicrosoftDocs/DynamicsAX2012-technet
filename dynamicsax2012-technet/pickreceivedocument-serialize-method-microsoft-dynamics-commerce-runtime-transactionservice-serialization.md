---
title: PickReceiveDocument.Serialize Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: Serialize Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument.Serialize(Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.pickreceivedocument.serialize(v=AX.60)
ms:contentKeyID: 62212653
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument.Serialize
dev_langs:
- CSharp
- C++
- VB
---

# Serialize Method

Serializes the specified picking receiving document.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Serialize ( _
    pickReceiveDocument As PickReceiveDocument _
) As String
'Usage
Dim pickReceiveDocument As PickReceiveDocument
Dim returnValue As String

returnValue = PickReceiveDocument.Serialize(pickReceiveDocument)
```

``` csharp
public static string Serialize(
    PickReceiveDocument pickReceiveDocument
)
```

``` c++
public:
static String^ Serialize(
    PickReceiveDocument^ pickReceiveDocument
)
```

#### Parameters

  - pickReceiveDocument  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Serialized string for the pick receive document.  

## See Also

#### Reference

[PickReceiveDocument Class](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

