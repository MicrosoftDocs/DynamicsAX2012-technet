---
title: TransactionServiceClient.InventoryLookup Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: InventoryLookup Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.InventoryLookup(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.inventorylookup(v=AX.60)
ms:contentKeyID: 49853283
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.InventoryLookup
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLookup Method

Gets the inventory lookup.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function InventoryLookup ( _
    itemId As String, _
    variantId As String _
) As ReadOnlyCollection(Of InventoryInfo)
'Usage
Dim instance As TransactionServiceClient
Dim itemId As String
Dim variantId As String
Dim returnValue As ReadOnlyCollection(Of InventoryInfo)

returnValue = instance.InventoryLookup(itemId, _
    variantId)
```

``` csharp
public ReadOnlyCollection<InventoryInfo> InventoryLookup(
    string itemId,
    string variantId
)
```

``` c++
public:
ReadOnlyCollection<InventoryInfo^>^ InventoryLookup(
    String^ itemId, 
    String^ variantId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[InventoryInfo](inventoryinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)\>  
A collection of inventory information.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

