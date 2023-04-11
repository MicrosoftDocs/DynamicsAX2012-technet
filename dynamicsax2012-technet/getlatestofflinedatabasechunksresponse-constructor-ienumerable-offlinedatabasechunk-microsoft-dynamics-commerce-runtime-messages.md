---
title: GetLatestOfflineDatabaseChunksResponse Constructor (IEnumerable(OfflineDatabaseChunk)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetLatestOfflineDatabaseChunksResponse Constructor (IEnumerable(OfflineDatabaseChunk))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLatestOfflineDatabaseChunksResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlatestofflinedatabasechunksresponse.getlatestofflinedatabasechunksresponse(v=AX.60)
ms:contentKeyID: 65316457
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetLatestOfflineDatabaseChunksResponse Constructor (IEnumerable(OfflineDatabaseChunk))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    chunks As IEnumerable(Of OfflineDatabaseChunk) _
)
'Usage
Dim chunks As IEnumerable(Of OfflineDatabaseChunk)

Dim instance As New GetLatestOfflineDatabaseChunksResponse(chunks)
```

``` csharp
public GetLatestOfflineDatabaseChunksResponse(
    IEnumerable<OfflineDatabaseChunk> chunks
)
```

``` c++
public:
GetLatestOfflineDatabaseChunksResponse(
    IEnumerable<OfflineDatabaseChunk^>^ chunks
)
```

#### Parameters

  - chunks  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLatestOfflineDatabaseChunksResponse Class](getlatestofflinedatabasechunksresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetLatestOfflineDatabaseChunksResponse Overload](getlatestofflinedatabasechunksresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

