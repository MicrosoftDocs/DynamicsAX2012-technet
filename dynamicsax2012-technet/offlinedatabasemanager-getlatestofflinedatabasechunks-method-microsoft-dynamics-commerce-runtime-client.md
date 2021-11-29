---
title: OfflineDatabaseManager.GetLatestOfflineDatabaseChunks Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLatestOfflineDatabaseChunks Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OfflineDatabaseManager.GetLatestOfflineDatabaseChunks(Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.offlinedatabasemanager.getlatestofflinedatabasechunks(v=AX.60)
ms:contentKeyID: 65320232
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OfflineDatabaseManager.GetLatestOfflineDatabaseChunks
dev_langs:
- CSharp
- C++
- VB
---

# GetLatestOfflineDatabaseChunks Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLatestOfflineDatabaseChunks ( _
    databaseType As OfflineDatabaseType _
) As IEnumerable(Of OfflineDatabaseChunk)
'Usage
Dim instance As OfflineDatabaseManager
Dim databaseType As OfflineDatabaseType
Dim returnValue As IEnumerable(Of OfflineDatabaseChunk)

returnValue = instance.GetLatestOfflineDatabaseChunks(databaseType)
```

``` csharp
public IEnumerable<OfflineDatabaseChunk> GetLatestOfflineDatabaseChunks(
    OfflineDatabaseType databaseType
)
```

``` c++
public:
IEnumerable<OfflineDatabaseChunk^>^ GetLatestOfflineDatabaseChunks(
    OfflineDatabaseType databaseType
)
```

#### Parameters

  - databaseType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseType](offlinedatabasetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OfflineDatabaseManager Class](offlinedatabasemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

