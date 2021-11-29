---
title: InventoryInfo.InventoryLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: InventoryLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo.InventoryLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.inventoryinfo.inventorylocationid(v=AX.60)
ms:contentKeyID: 49832355
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo.InventoryLocationId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the inventory location identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property InventoryLocationId As String
    Get
    Set
'Usage
Dim instance As InventoryInfo
Dim value As String

value = instance.InventoryLocationId

instance.InventoryLocationId = value
```

``` csharp
public string InventoryLocationId { get; set; }
```

``` c++
public:
property String^ InventoryLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The inventory location identifier.  

## See Also

#### Reference

[InventoryInfo Class](inventoryinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

