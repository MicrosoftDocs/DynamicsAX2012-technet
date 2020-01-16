---
title: InventoryManager.DeleteStockCountJournalTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: DeleteStockCountJournalTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.DeleteStockCountJournalTransactions(System.String,System.String,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.deletestockcountjournaltransactions(v=AX.60)
ms:contentKeyID: 62214459
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.DeleteStockCountJournalTransactions
dev_langs:
- CSharp
- C++
- VB
---

# DeleteStockCountJournalTransactions Method

Deletes the stock count transaction for the given journalId and item identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub DeleteStockCountJournalTransactions ( _
    journalId As String, _
    itemId As String, _
    inventSizeId As String, _
    inventColorId As String, _
    inventStyleId As String, _
    configId As String _
)
'Usage
Dim instance As InventoryManager
Dim journalId As String
Dim itemId As String
Dim inventSizeId As String
Dim inventColorId As String
Dim inventStyleId As String
Dim configId As String

instance.DeleteStockCountJournalTransactions(journalId, _
    itemId, inventSizeId, inventColorId, _
    inventStyleId, configId)
```

``` csharp
public void DeleteStockCountJournalTransactions(
    string journalId,
    string itemId,
    string inventSizeId,
    string inventColorId,
    string inventStyleId,
    string configId
)
```

``` c++
public:
void DeleteStockCountJournalTransactions(
    String^ journalId, 
    String^ itemId, 
    String^ inventSizeId, 
    String^ inventColorId, 
    String^ inventStyleId, 
    String^ configId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventSizeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventColorId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventStyleId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - configId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

