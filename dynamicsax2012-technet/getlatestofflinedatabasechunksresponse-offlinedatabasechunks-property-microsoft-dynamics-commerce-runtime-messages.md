---
title: GetLatestOfflineDatabaseChunksResponse.OfflineDatabaseChunks Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OfflineDatabaseChunks Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLatestOfflineDatabaseChunksResponse.OfflineDatabaseChunks
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlatestofflinedatabasechunksresponse.offlinedatabasechunks(v=AX.60)
ms:contentKeyID: 65320695
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetLatestOfflineDatabaseChunksResponse.OfflineDatabaseChunks
dev_langs:
- CSharp
- C++
- VB
---

# OfflineDatabaseChunks Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OfflineDatabaseChunks As ReadOnlyCollection(Of OfflineDatabaseChunk)
    Get
    Private Set
'Usage
Dim instance As GetLatestOfflineDatabaseChunksResponse
Dim value As ReadOnlyCollection(Of OfflineDatabaseChunk)

value = instance.OfflineDatabaseChunks
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<OfflineDatabaseChunk> OfflineDatabaseChunks { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<OfflineDatabaseChunk^>^ OfflineDatabaseChunks {
    ReadOnlyCollection<OfflineDatabaseChunk^>^ get ();
    private: void set (ReadOnlyCollection<OfflineDatabaseChunk^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLatestOfflineDatabaseChunksResponse Class](getlatestofflinedatabasechunksresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

