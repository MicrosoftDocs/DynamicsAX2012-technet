---
title: TableType.DataTable Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: DataTable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.TableType.DataTable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.tabletype.datatable(v=AX.60)
ms:contentKeyID: 65322123
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.TableType.DataTable
dev_langs:
- CSharp
- C++
- VB
---

# DataTable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the underlying data table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property DataTable As DataTable
    Get
'Usage
Dim instance As TableType
Dim value As DataTable

value = instance.DataTable
```

``` csharp
public DataTable DataTable { get; }
```

``` c++
public:
property DataTable^ DataTable {
    DataTable^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md).  

## Remarks

This data table should NOT be disposed by the caller directly.

## See Also

#### Reference

[TableType Class](tabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

