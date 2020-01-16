---
title: IStoreInventoryServicesV1.GetStockCountJournalTransactions Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetStockCountJournalTransactions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.GetStockCountJournalTransactions(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.istoreinventoryservicesv1.getstockcountjournaltransactions(v=AX.60)
ms:contentKeyID: 47344347
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.GetStockCountJournalTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournalTransactions Method

Get list of stock count journal transactions by journal ID with HQ.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetStockCountJournalTransactions ( _
    journalId As String _
) As IList(Of ISCJournalTransaction)
'Usage
Dim instance As IStoreInventoryServicesV1
Dim journalId As String
Dim returnValue As IList(Of ISCJournalTransaction)

returnValue = instance.GetStockCountJournalTransactions(journalId)
```

``` csharp
IList<ISCJournalTransaction> GetStockCountJournalTransactions(
    string journalId
)
```

``` c++
IList<ISCJournalTransaction^>^ GetStockCountJournalTransactions(
    String^ journalId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ISCJournalTransaction](iscjournaltransaction-interface-microsoft-dynamics-retail-pos-contracts-services.md)\>  
A list of transaction journals.  

## See Also

#### Reference

[IStoreInventoryServicesV1 Interface](istoreinventoryservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

