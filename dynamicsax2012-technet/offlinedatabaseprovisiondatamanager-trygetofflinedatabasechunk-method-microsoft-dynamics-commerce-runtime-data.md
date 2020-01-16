---
title: OfflineDatabaseProvisionDataManager.TryGetOfflineDatabaseChunk Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TryGetOfflineDatabaseChunk Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.OfflineDatabaseProvisionDataManager.TryGetOfflineDatabaseChunk(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.offlinedatabaseprovisiondatamanager.trygetofflinedatabasechunk(v=AX.60)
ms:contentKeyID: 65322800
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.OfflineDatabaseProvisionDataManager.TryGetOfflineDatabaseChunk
dev_langs:
- CSharp
- C++
- VB
---

# TryGetOfflineDatabaseChunk Method

Tries to get the offline database chunk. A return value indicates whether the operation succeeded or failed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function TryGetOfflineDatabaseChunk ( _
    recordId As Long, _
    <OutAttribute> ByRef offlineDatabaseChunk As OfflineDatabaseChunk _
) As Boolean
'Usage
Dim instance As OfflineDatabaseProvisionDataManager
Dim recordId As Long
Dim offlineDatabaseChunk As OfflineDatabaseChunk
Dim returnValue As Boolean

returnValue = instance.TryGetOfflineDatabaseChunk(recordId, _
    offlineDatabaseChunk)
```

``` csharp
public bool TryGetOfflineDatabaseChunk(
    long recordId,
    out OfflineDatabaseChunk offlineDatabaseChunk
)
```

``` c++
public:
virtual bool TryGetOfflineDatabaseChunk(
    long long recordId, 
    [OutAttribute] OfflineDatabaseChunk^% offlineDatabaseChunk
) sealed
```

#### Parameters

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - offlineDatabaseChunk  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if chunk was retrieved successfully; otherwise, false.  

#### Implements

[IOfflineProvisionDataManager.TryGetOfflineDatabaseChunk(Int64, OfflineDatabaseChunk)](iofflineprovisiondatamanager-trygetofflinedatabasechunk-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[OfflineDatabaseProvisionDataManager Class](offlinedatabaseprovisiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

