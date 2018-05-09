---
title: IStoreInventoryServicesV1.GetStockCountJournals Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetStockCountJournals Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.GetStockCountJournals
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.istoreinventoryservicesv1.getstockcountjournals(v=AX.60)
ms:contentKeyID: 47344157
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.GetStockCountJournals
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournals Method

Sync the local list of stock count journals with HQ.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetStockCountJournals As IList(Of ISCJournal)
'Usage
Dim instance As IStoreInventoryServicesV1
Dim returnValue As IList(Of ISCJournal)

returnValue = instance.GetStockCountJournals()
```

``` csharp
IList<ISCJournal> GetStockCountJournals()
```

``` c++
IList<ISCJournal^>^ GetStockCountJournals()
```

#### Return Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[ISCJournal](iscjournal-interface-microsoft-dynamics-retail-pos-contracts-services.md)\>  
A list of stock count journals.  

## See Also

#### Reference

[IStoreInventoryServicesV1 Interface](istoreinventoryservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

