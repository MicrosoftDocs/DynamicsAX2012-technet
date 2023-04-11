---
title: StoreOperationsManager.GetOfflineSyncStats Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOfflineSyncStats Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetOfflineSyncStats
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.getofflinesyncstats(v=AX.60)
ms:contentKeyID: 65320906
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetOfflineSyncStats
dev_langs:
- CSharp
- C++
- VB
---

# GetOfflineSyncStats Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOfflineSyncStats As IEnumerable(Of OfflineSyncStatsLine)
'Usage
Dim instance As StoreOperationsManager
Dim returnValue As IEnumerable(Of OfflineSyncStatsLine)

returnValue = instance.GetOfflineSyncStats()
```

``` csharp
public IEnumerable<OfflineSyncStatsLine> GetOfflineSyncStats()
```

``` c++
public:
IEnumerable<OfflineSyncStatsLine^>^ GetOfflineSyncStats()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OfflineSyncStatsLine](offlinesyncstatsline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

