---
title: ItemReturn.Serialize Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: Serialize Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn.Serialize(Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.itemreturn.serialize(v=AX.60)
ms:contentKeyID: 49855596
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn.Serialize
dev_langs:
- CSharp
- C++
- VB
---

# Serialize Method

Serializes the specified item to an XML string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Serialize ( _
    itemReturn As ItemReturn _
) As String
'Usage
Dim itemReturn As ItemReturn
Dim returnValue As String

returnValue = ItemReturn.Serialize(itemReturn)
```

``` csharp
public static string Serialize(
    ItemReturn itemReturn
)
```

``` c++
public:
static String^ Serialize(
    ItemReturn^ itemReturn
)
```

#### Parameters

  - itemReturn  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn](itemreturn-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
An XML string.  

## See Also

#### Reference

[ItemReturn Class](itemreturn-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

