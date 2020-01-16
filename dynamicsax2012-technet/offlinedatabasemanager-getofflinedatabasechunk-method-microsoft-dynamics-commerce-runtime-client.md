---
title: OfflineDatabaseManager.GetOfflineDatabaseChunk Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOfflineDatabaseChunk Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OfflineDatabaseManager.GetOfflineDatabaseChunk(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.offlinedatabasemanager.getofflinedatabasechunk(v=AX.60)
ms:contentKeyID: 65317987
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OfflineDatabaseManager.GetOfflineDatabaseChunk
dev_langs:
- CSharp
- C++
- VB
---

# GetOfflineDatabaseChunk Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOfflineDatabaseChunk ( _
    recordId As Long _
) As OfflineDatabaseChunk
'Usage
Dim instance As OfflineDatabaseManager
Dim recordId As Long
Dim returnValue As OfflineDatabaseChunk

returnValue = instance.GetOfflineDatabaseChunk(recordId)
```

``` csharp
public OfflineDatabaseChunk GetOfflineDatabaseChunk(
    long recordId
)
```

``` c++
public:
OfflineDatabaseChunk^ GetOfflineDatabaseChunk(
    long long recordId
)
```

#### Parameters

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OfflineDatabaseManager Class](offlinedatabasemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

