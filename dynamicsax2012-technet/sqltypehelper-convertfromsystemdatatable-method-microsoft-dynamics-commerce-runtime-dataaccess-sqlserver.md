---
title: SqlTypeHelper.ConvertFromSystemDataTable Method  (Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer)
TOCTitle: ConvertFromSystemDataTable Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlTypeHelper.ConvertFromSystemDataTable(System.Data.DataTable)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataaccess.sqlserver.sqltypehelper.convertfromsystemdatatable(v=AX.60)
ms:contentKeyID: 65322282
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlTypeHelper.ConvertFromSystemDataTable
dev_langs:
- CSharp
- C++
- VB
---

# ConvertFromSystemDataTable Method

Converts a [DataTable](https://technet.microsoft.com/en-us/library/9186hy08\(v=ax.60\)) into a [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertFromSystemDataTable ( _
    dataTable As DataTable _
) As DataTable
'Usage
Dim dataTable As DataTable
Dim returnValue As DataTable

returnValue = SqlTypeHelper.ConvertFromSystemDataTable(dataTable)
```

``` csharp
public static DataTable ConvertFromSystemDataTable(
    DataTable dataTable
)
```

``` c++
public:
static DataTable^ ConvertFromSystemDataTable(
    DataTable^ dataTable
)
```

#### Parameters

  - dataTable  
    Type: [System.Data.DataTable](https://technet.microsoft.com/en-us/library/9186hy08\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  
The converted data table.  

## See Also

#### Reference

[SqlTypeHelper Class](sqltypehelper-class-microsoft-dynamics-commerce-runtime-dataaccess-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)

