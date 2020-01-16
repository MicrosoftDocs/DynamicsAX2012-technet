---
title: InventoryInfo.Deserialize Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: Deserialize Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo.Deserialize(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.inventoryinfo.deserialize(v=AX.60)
ms:contentKeyID: 49822692
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo.Deserialize
dev_langs:
- CSharp
- C++
- VB
---

# Deserialize Method

Deserializes the specified source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Deserialize ( _
    source As String _
) As InventoryInfo
'Usage
Dim source As String
Dim returnValue As InventoryInfo

returnValue = InventoryInfo.Deserialize(source)
```

``` csharp
public static InventoryInfo Deserialize(
    string source
)
```

``` c++
public:
static InventoryInfo^ Deserialize(
    String^ source
)
```

#### Parameters

  - source  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo](inventoryinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
Deserialized InventoryInfo instance from source.  

## See Also

#### Reference

[InventoryInfo Class](inventoryinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

