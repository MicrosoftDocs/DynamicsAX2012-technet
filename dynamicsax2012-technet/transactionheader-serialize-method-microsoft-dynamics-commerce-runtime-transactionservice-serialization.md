---
title: TransactionHeader.Serialize Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: Serialize Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader.Serialize(Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionheader.serialize(v=AX.60)
ms:contentKeyID: 49853651
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader.Serialize
dev_langs:
- CSharp
- C++
- VB
---

# Serialize Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Serializes the specified transaction header.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Serialize ( _
    transactionHeader As TransactionHeader _
) As String
'Usage
Dim transactionHeader As TransactionHeader
Dim returnValue As String

returnValue = TransactionHeader.Serialize(transactionHeader)
```

``` csharp
public static string Serialize(
    TransactionHeader transactionHeader
)
```

``` c++
public:
static String^ Serialize(
    TransactionHeader^ transactionHeader
)
```

#### Parameters

  - transactionHeader  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader](transactionheader-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
TransactionHeader serialized into a string.  

## See Also

#### Reference

[TransactionHeader Class](transactionheader-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

