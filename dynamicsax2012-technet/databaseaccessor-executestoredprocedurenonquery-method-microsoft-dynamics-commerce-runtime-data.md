---
title: DatabaseAccessor.ExecuteStoredProcedureNonQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedureNonQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedureNonQuery(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databaseaccessor.executestoredprocedurenonquery(v=AX.60)
ms:contentKeyID: 62209088
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedureNonQuery
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteStoredProcedureNonQuery Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the specified stored procedure with the specified parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteStoredProcedureNonQuery ( _
    procedureName As String, _
    parameters As ParameterSet _
) As Integer
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim returnValue As Integer

returnValue = Me.ExecuteStoredProcedureNonQuery(procedureName, _
    parameters)
```

``` csharp
protected int ExecuteStoredProcedureNonQuery(
    string procedureName,
    ParameterSet parameters
)
```

``` c++
protected:
int ExecuteStoredProcedureNonQuery(
    String^ procedureName, 
    ParameterSet^ parameters
)
```

#### Parameters

  - procedureName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The error code returned from the stored procedure.  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

