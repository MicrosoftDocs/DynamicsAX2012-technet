---
title: IStoreInventoryServicesV1.CommitStockCounts Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CommitStockCounts Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.CommitStockCounts(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.istoreinventoryservicesv1.commitstockcounts(v=AX.60)
ms:contentKeyID: 47343879
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.CommitStockCounts
dev_langs:
- CSharp
- C++
- VB
---

# CommitStockCounts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Commits stock counts by sending them back to HQ.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CommitStockCounts ( _
    journalId As String, _
    recId As String _
) As ISCJournal
'Usage
Dim instance As IStoreInventoryServicesV1
Dim journalId As String
Dim recId As String
Dim returnValue As ISCJournal

returnValue = instance.CommitStockCounts(journalId, _
    recId)
```

``` csharp
ISCJournal CommitStockCounts(
    string journalId,
    string recId
)
```

``` c++
ISCJournal^ CommitStockCounts(
    String^ journalId, 
    String^ recId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - recId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournal](iscjournal-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The stock count journal.  

## See Also

#### Reference

[IStoreInventoryServicesV1 Interface](istoreinventoryservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

