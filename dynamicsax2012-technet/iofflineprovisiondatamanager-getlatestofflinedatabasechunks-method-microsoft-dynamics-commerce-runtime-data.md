---
title: IOfflineProvisionDataManager.GetLatestOfflineDatabaseChunks Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLatestOfflineDatabaseChunks Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IOfflineProvisionDataManager.GetLatestOfflineDatabaseChunks(Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseType,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.iofflineprovisiondatamanager.getlatestofflinedatabasechunks(v=AX.60)
ms:contentKeyID: 65321640
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IOfflineProvisionDataManager.GetLatestOfflineDatabaseChunks
dev_langs:
- CSharp
- C++
- VB
---

# GetLatestOfflineDatabaseChunks Method

Gets the chunks collection of the latest offline database of the given database type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetLatestOfflineDatabaseChunks ( _
    databaseType As OfflineDatabaseType, _
    channelId As Long _
) As IEnumerable(Of OfflineDatabaseChunk)
'Usage
Dim instance As IOfflineProvisionDataManager
Dim databaseType As OfflineDatabaseType
Dim channelId As Long
Dim returnValue As IEnumerable(Of OfflineDatabaseChunk)

returnValue = instance.GetLatestOfflineDatabaseChunks(databaseType, _
    channelId)
```

``` csharp
IEnumerable<OfflineDatabaseChunk> GetLatestOfflineDatabaseChunks(
    OfflineDatabaseType databaseType,
    long channelId
)
```

``` c++
IEnumerable<OfflineDatabaseChunk^>^ GetLatestOfflineDatabaseChunks(
    OfflineDatabaseType databaseType, 
    long long channelId
)
```

#### Parameters

  - databaseType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseType](offlinedatabasetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
[OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md) collection.  

## See Also

#### Reference

[IOfflineProvisionDataManager Interface](iofflineprovisiondatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

