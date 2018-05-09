---
title: IOfflineProvisionDataManager.TryGetOfflineDatabaseChunk Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TryGetOfflineDatabaseChunk Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IOfflineProvisionDataManager.TryGetOfflineDatabaseChunk(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.iofflineprovisiondatamanager.trygetofflinedatabasechunk(v=AX.60)
ms:contentKeyID: 65319044
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IOfflineProvisionDataManager.TryGetOfflineDatabaseChunk
dev_langs:
- CSharp
- C++
- VB
---

# TryGetOfflineDatabaseChunk Method

Tries to get the latest offline database chunk.

A return value indicates whether the operation succeeded or failed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function TryGetOfflineDatabaseChunk ( _
    recordId As Long, _
    <OutAttribute> ByRef offlineDatabaseChunk As OfflineDatabaseChunk _
) As Boolean
'Usage
Dim instance As IOfflineProvisionDataManager
Dim recordId As Long
Dim offlineDatabaseChunk As OfflineDatabaseChunk
Dim returnValue As Boolean

returnValue = instance.TryGetOfflineDatabaseChunk(recordId, _
    offlineDatabaseChunk)
```

``` csharp
bool TryGetOfflineDatabaseChunk(
    long recordId,
    out OfflineDatabaseChunk offlineDatabaseChunk
)
```

``` c++
bool TryGetOfflineDatabaseChunk(
    long long recordId, 
    [OutAttribute] OfflineDatabaseChunk^% offlineDatabaseChunk
)
```

#### Parameters

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - offlineDatabaseChunk  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if metadata was retrieved successfully; otherwise, false.  

## See Also

#### Reference

[IOfflineProvisionDataManager Interface](iofflineprovisiondatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

