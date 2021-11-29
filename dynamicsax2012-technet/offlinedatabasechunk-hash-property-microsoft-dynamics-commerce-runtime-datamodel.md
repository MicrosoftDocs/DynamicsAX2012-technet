---
title: OfflineDatabaseChunk.Hash Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Hash Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.Hash
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.offlinedatabasechunk.hash(v=AX.60)
ms:contentKeyID: 65320641
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.Hash
dev_langs:
- CSharp
- C++
- VB
---

# Hash Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the hash of database file.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("HASH")> _
<DataMemberAttribute> _
Public Property Hash As String
    Get
    Set
'Usage
Dim instance As OfflineDatabaseChunk
Dim value As String

value = instance.Hash

instance.Hash = value
```

``` csharp
[ColumnAttribute("HASH")]
[DataMemberAttribute]
public string Hash { get; set; }
```

``` c++
[ColumnAttribute(L"HASH")]
[DataMemberAttribute]
public:
property String^ Hash {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OfflineDatabaseChunk Class](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

