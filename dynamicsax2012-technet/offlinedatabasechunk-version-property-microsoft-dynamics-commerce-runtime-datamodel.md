---
title: OfflineDatabaseChunk.Version Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Version Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.Version
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.offlinedatabasechunk.version(v=AX.60)
ms:contentKeyID: 65321780
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.Version
dev_langs:
- CSharp
- C++
- VB
---

# Version Property

Gets or sets the database version of chunk.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VERSION")> _
<DataMemberAttribute> _
Public Property Version As Long
    Get
    Set
'Usage
Dim instance As OfflineDatabaseChunk
Dim value As Long

value = instance.Version

instance.Version = value
```

``` csharp
[ColumnAttribute("VERSION")]
[DataMemberAttribute]
public long Version { get; set; }
```

``` c++
[ColumnAttribute(L"VERSION")]
[DataMemberAttribute]
public:
property long long Version {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[OfflineDatabaseChunk Class](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

