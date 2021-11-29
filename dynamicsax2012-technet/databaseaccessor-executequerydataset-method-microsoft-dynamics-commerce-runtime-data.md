---
title: DatabaseAccessor.ExecuteQueryDataSet Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteQueryDataSet Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteQueryDataSet(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databaseaccessor.executequerydataset(v=AX.60)
ms:contentKeyID: 62212338
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteQueryDataSet
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteQueryDataSet Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the query with specified parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteQueryDataSet ( _
    query As String, _
    parameters As ParameterSet _
) As DataSet
'Usage
Dim query As String
Dim parameters As ParameterSet
Dim returnValue As DataSet

returnValue = Me.ExecuteQueryDataSet(query, _
    parameters)
```

``` csharp
protected DataSet ExecuteQueryDataSet(
    string query,
    ParameterSet parameters
)
```

``` c++
protected:
DataSet^ ExecuteQueryDataSet(
    String^ query, 
    ParameterSet^ parameters
)
```

#### Parameters

  - query  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md)  
A dataset.  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

