---
title: ItemReturn.Deserialize Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: Deserialize Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn.Deserialize(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.itemreturn.deserialize(v=AX.60)
ms:contentKeyID: 49831054
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn.Deserialize
dev_langs:
- CSharp
- C++
- VB
---

# Deserialize Method

Deserializes the specified source XML to the [ItemReturn](itemreturn-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md) object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Deserialize ( _
    source As String _
) As ItemReturn
'Usage
Dim source As String
Dim returnValue As ItemReturn

returnValue = ItemReturn.Deserialize(source)
```

``` csharp
public static ItemReturn Deserialize(
    string source
)
```

``` c++
public:
static ItemReturn^ Deserialize(
    String^ source
)
```

#### Parameters

  - source  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn](itemreturn-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
The item return object.  

## See Also

#### Reference

[ItemReturn Class](itemreturn-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

