---
title: InventoryInfo.Serialize Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: Serialize Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo.Serialize(Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.inventoryinfo.serialize(v=AX.60)
ms:contentKeyID: 49855997
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo.Serialize
dev_langs:
- CSharp
- C++
- VB
---

# Serialize Method

Serializes the specified inventory info.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Serialize ( _
    inventoryInfo As InventoryInfo _
) As String
'Usage
Dim inventoryInfo As InventoryInfo
Dim returnValue As String

returnValue = InventoryInfo.Serialize(inventoryInfo)
```

``` csharp
public static string Serialize(
    InventoryInfo inventoryInfo
)
```

``` c++
public:
static String^ Serialize(
    InventoryInfo^ inventoryInfo
)
```

#### Parameters

  - inventoryInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo](inventoryinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Serialized string for inventoryInfo.  

## See Also

#### Reference

[InventoryInfo Class](inventoryinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

