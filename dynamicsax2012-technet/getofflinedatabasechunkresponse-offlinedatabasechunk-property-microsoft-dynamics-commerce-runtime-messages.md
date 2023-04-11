---
title: GetOfflineDatabaseChunkResponse.OfflineDatabaseChunk Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OfflineDatabaseChunk Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineDatabaseChunkResponse.OfflineDatabaseChunk
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getofflinedatabasechunkresponse.offlinedatabasechunk(v=AX.60)
ms:contentKeyID: 65316627
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineDatabaseChunkResponse.OfflineDatabaseChunk
dev_langs:
- CSharp
- C++
- VB
---

# OfflineDatabaseChunk Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OfflineDatabaseChunk As OfflineDatabaseChunk
    Get
    Private Set
'Usage
Dim instance As GetOfflineDatabaseChunkResponse
Dim value As OfflineDatabaseChunk

value = instance.OfflineDatabaseChunk
```

``` csharp
[DataMemberAttribute]
public OfflineDatabaseChunk OfflineDatabaseChunk { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property OfflineDatabaseChunk^ OfflineDatabaseChunk {
    OfflineDatabaseChunk^ get ();
    private: void set (OfflineDatabaseChunk^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetOfflineDatabaseChunkResponse Class](getofflinedatabasechunkresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

