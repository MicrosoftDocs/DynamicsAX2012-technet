---
title: TransactionItem.Deserialize Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: Deserialize Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.Deserialize(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.deserialize(v=AX.60)
ms:contentKeyID: 49852820
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.Deserialize
dev_langs:
- CSharp
- C++
- VB
---

# Deserialize Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deserializes the specified serialized XML string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Deserialize ( _
    serializedXml As String _
) As TransactionItem
'Usage
Dim serializedXml As String
Dim returnValue As TransactionItem

returnValue = TransactionItem.Deserialize(serializedXml)
```

``` csharp
public static TransactionItem Deserialize(
    string serializedXml
)
```

``` c++
public:
static TransactionItem^ Deserialize(
    String^ serializedXml
)
```

#### Parameters

  - serializedXml  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
TransactionItem instance deserialized from input.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

