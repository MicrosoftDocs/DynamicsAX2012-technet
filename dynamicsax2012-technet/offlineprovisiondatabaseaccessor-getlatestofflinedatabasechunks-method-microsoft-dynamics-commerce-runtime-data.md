---
title: OfflineProvisionDatabaseAccessor.GetLatestOfflineDatabaseChunks Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLatestOfflineDatabaseChunks Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.OfflineProvisionDatabaseAccessor.GetLatestOfflineDatabaseChunks(Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseType,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.offlineprovisiondatabaseaccessor.getlatestofflinedatabasechunks(v=AX.60)
ms:contentKeyID: 65322178
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.OfflineProvisionDatabaseAccessor.GetLatestOfflineDatabaseChunks
dev_langs:
- CSharp
- C++
- VB
---

# GetLatestOfflineDatabaseChunks Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of chunks by the database record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetLatestOfflineDatabaseChunks ( _
    databaseType As OfflineDatabaseType, _
    channelId As Long _
) As IEnumerable(Of OfflineDatabaseChunk)
'Usage
Dim instance As OfflineProvisionDatabaseAccessor
Dim databaseType As OfflineDatabaseType
Dim channelId As Long
Dim returnValue As IEnumerable(Of OfflineDatabaseChunk)

returnValue = instance.GetLatestOfflineDatabaseChunks(databaseType, _
    channelId)
```

``` csharp
public IEnumerable<OfflineDatabaseChunk> GetLatestOfflineDatabaseChunks(
    OfflineDatabaseType databaseType,
    long channelId
)
```

``` c++
public:
virtual IEnumerable<OfflineDatabaseChunk^>^ GetLatestOfflineDatabaseChunks(
    OfflineDatabaseType databaseType, 
    long long channelId
) sealed
```

#### Parameters

  - databaseType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseType](offlinedatabasetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A new instance of the [OfflineProvisionDatabaseAccessor](offlineprovisiondatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md) class.  

#### Implements

[IOfflineProvisionDataManager.GetLatestOfflineDatabaseChunks(OfflineDatabaseType, Int64)](iofflineprovisiondatamanager-getlatestofflinedatabasechunks-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[OfflineProvisionDatabaseAccessor Class](offlineprovisiondatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

