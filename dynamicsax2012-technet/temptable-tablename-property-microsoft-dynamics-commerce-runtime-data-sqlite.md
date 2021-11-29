---
title: TempTable.TableName Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: TableName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.TempTable.TableName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.temptable.tablename(v=AX.60)
ms:contentKeyID: 65322176
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.TempTable.TableName
dev_langs:
- CSharp
- C++
- VB
---

# TableName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the table name for this [TempTable](temptable-class-microsoft-dynamics-commerce-runtime-data-sqlite.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property TableName As String
    Get
'Usage
Dim instance As TempTable
Dim value As String

value = instance.TableName
```

``` csharp
public string TableName { get; }
```

``` c++
public:
property String^ TableName {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TempTable Class](temptable-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

