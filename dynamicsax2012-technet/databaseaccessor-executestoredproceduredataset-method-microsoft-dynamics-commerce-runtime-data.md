---
title: DatabaseAccessor.ExecuteStoredProcedureDataSet Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedureDataSet Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedureDataSet(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.databaseaccessor.executestoredproceduredataset(v=AX.60)
ms:contentKeyID: 65322279
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedureDataSet
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteStoredProcedureDataSet Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteStoredProcedureDataSet ( _
    procedureName As String, _
    parameters As ParameterSet, _
    settings As QueryResultSettings _
) As DataSet
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim settings As QueryResultSettings
Dim returnValue As DataSet

returnValue = Me.ExecuteStoredProcedureDataSet(procedureName, _
    parameters, settings)
```

``` csharp
protected DataSet ExecuteStoredProcedureDataSet(
    string procedureName,
    ParameterSet parameters,
    QueryResultSettings settings
)
```

``` c++
protected:
DataSet^ ExecuteStoredProcedureDataSet(
    String^ procedureName, 
    ParameterSet^ parameters, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - procedureName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

