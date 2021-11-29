---
title: OfflineDatabaseChunk.DatabaseType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DatabaseType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.DatabaseType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.offlinedatabasechunk.databasetype(v=AX.60)
ms:contentKeyID: 65319534
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.DatabaseType
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the database type identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DATABASETYPE")> _
Public Property DatabaseType As OfflineDatabaseType
    Get
    Friend Set
'Usage
Dim instance As OfflineDatabaseChunk
Dim value As OfflineDatabaseType

value = instance.DatabaseType
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DATABASETYPE")]
public OfflineDatabaseType DatabaseType { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DATABASETYPE")]
public:
property OfflineDatabaseType DatabaseType {
    OfflineDatabaseType get ();
    internal: void set (OfflineDatabaseType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseType](offlinedatabasetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [OfflineDatabaseType](offlinedatabasetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OfflineDatabaseChunk Class](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

