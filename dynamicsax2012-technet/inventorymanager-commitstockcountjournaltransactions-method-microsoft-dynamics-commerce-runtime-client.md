---
title: InventoryManager.CommitStockCountJournalTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CommitStockCountJournalTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.CommitStockCountJournalTransactions(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.commitstockcountjournaltransactions(v=AX.60)
ms:contentKeyID: 62209961
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.CommitStockCountJournalTransactions
dev_langs:
- CSharp
- C++
- VB
---

# CommitStockCountJournalTransactions Method

Commits the list of Stock journal transactions to AX.

After successfull commit, all the journal and transactions are deleted from the RetailServer Db.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub CommitStockCountJournalTransactions ( _
    journalId As String _
)
'Usage
Dim instance As InventoryManager
Dim journalId As String

instance.CommitStockCountJournalTransactions(journalId)
```

``` csharp
public void CommitStockCountJournalTransactions(
    string journalId
)
```

``` c++
public:
void CommitStockCountJournalTransactions(
    String^ journalId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

