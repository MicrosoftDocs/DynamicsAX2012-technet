---
title: SqlTypeHelper.ConvertToSystemDataTable Method  (Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer)
TOCTitle: ConvertToSystemDataTable Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlTypeHelper.ConvertToSystemDataTable(Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataaccess.sqlserver.sqltypehelper.converttosystemdatatable(v=AX.60)
ms:contentKeyID: 65321012
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlTypeHelper.ConvertToSystemDataTable
dev_langs:
- CSharp
- C++
- VB
---

# ConvertToSystemDataTable Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts a [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md) into a [DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertToSystemDataTable ( _
    dataTable As DataTable _
) As DataTable
'Usage
Dim dataTable As DataTable
Dim returnValue As DataTable

returnValue = SqlTypeHelper.ConvertToSystemDataTable(dataTable)
```

``` csharp
public static DataTable ConvertToSystemDataTable(
    DataTable dataTable
)
```

``` c++
public:
static DataTable^ ConvertToSystemDataTable(
    DataTable^ dataTable
)
```

#### Parameters

  - dataTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Return Value

Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  
The converted data table.  

## See Also

#### Reference

[SqlTypeHelper Class](sqltypehelper-class-microsoft-dynamics-commerce-runtime-dataaccess-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)

