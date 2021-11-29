---
title: TransactionItem.Serialize Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: Serialize Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.Serialize(Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.serialize(v=AX.60)
ms:contentKeyID: 49856230
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.Serialize
dev_langs:
- CSharp
- C++
- VB
---

# Serialize Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Serializes the specified transaction item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Serialize ( _
    transactionItem As TransactionItem _
) As String
'Usage
Dim transactionItem As TransactionItem
Dim returnValue As String

returnValue = TransactionItem.Serialize(transactionItem)
```

``` csharp
public static string Serialize(
    TransactionItem transactionItem
)
```

``` c++
public:
static String^ Serialize(
    TransactionItem^ transactionItem
)
```

#### Parameters

  - transactionItem  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The serialized string of the transaction item.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

