---
title: SqlTypeHelper.ConvertFromSystemDataSet Method  (Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer)
TOCTitle: ConvertFromSystemDataSet Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlTypeHelper.ConvertFromSystemDataSet(System.Data.DataSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataaccess.sqlserver.sqltypehelper.convertfromsystemdataset(v=AX.60)
ms:contentKeyID: 65322087
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.SqlTypeHelper.ConvertFromSystemDataSet
dev_langs:
- CSharp
- C++
- VB
---

# ConvertFromSystemDataSet Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts a [DataSet](https://technet.microsoft.com/library/bwy42y0e\(v=ax.60\)) into a [DataSet](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertFromSystemDataSet ( _
    dataSet As DataSet _
) As DataSet
'Usage
Dim dataSet As DataSet
Dim returnValue As DataSet

returnValue = SqlTypeHelper.ConvertFromSystemDataSet(dataSet)
```

``` csharp
public static DataSet ConvertFromSystemDataSet(
    DataSet dataSet
)
```

``` c++
public:
static DataSet^ ConvertFromSystemDataSet(
    DataSet^ dataSet
)
```

#### Parameters

  - dataSet  
    Type: [System.Data.DataSet](https://technet.microsoft.com/library/bwy42y0e\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md)  
The converted dataset.  

## See Also

#### Reference

[SqlTypeHelper Class](sqltypehelper-class-microsoft-dynamics-commerce-runtime-dataaccess-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataAccess.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataaccess-sqlserver-namespace.md)

