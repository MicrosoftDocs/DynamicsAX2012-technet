---
title: InventoryManager.DeleteStockCountJournal Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: DeleteStockCountJournal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.DeleteStockCountJournal(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.deletestockcountjournal(v=AX.60)
ms:contentKeyID: 62207248
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.DeleteStockCountJournal
dev_langs:
- CSharp
- C++
- VB
---

# DeleteStockCountJournal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes the stock count journal for the given journalId in cascade.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub DeleteStockCountJournal ( _
    journalId As String _
)
'Usage
Dim instance As InventoryManager
Dim journalId As String

instance.DeleteStockCountJournal(journalId)
```

``` csharp
public void DeleteStockCountJournal(
    string journalId
)
```

``` c++
public:
void DeleteStockCountJournal(
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

