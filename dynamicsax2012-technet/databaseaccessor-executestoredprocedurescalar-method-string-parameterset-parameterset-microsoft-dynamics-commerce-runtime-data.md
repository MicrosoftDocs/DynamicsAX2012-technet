---
title: DatabaseAccessor.ExecuteStoredProcedureScalar Method (String, ParameterSet, ParameterSet) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedureScalar Method (String, ParameterSet, ParameterSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedureScalar(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet,Microsoft.Dynamics.Commerce.Runtime.ParameterSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databaseaccessor.executestoredprocedurescalar(v=AX.60)
ms:contentKeyID: 62203735
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ExecuteStoredProcedureScalar Method (String, ParameterSet, ParameterSet)

Executes the stored procedure using the specified parameters and returns the return value of the stored procedure as an integer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteStoredProcedureScalar ( _
    procedureName As String, _
    parameters As ParameterSet, _
    outputParameters As ParameterSet _
) As Integer
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim outputParameters As ParameterSet
Dim returnValue As Integer

returnValue = Me.ExecuteStoredProcedureScalar(procedureName, _
    parameters, outputParameters)
```

``` csharp
protected int ExecuteStoredProcedureScalar(
    string procedureName,
    ParameterSet parameters,
    ParameterSet outputParameters
)
```

``` c++
protected:
int ExecuteStoredProcedureScalar(
    String^ procedureName, 
    ParameterSet^ parameters, 
    ParameterSet^ outputParameters
)
```

#### Parameters

  - procedureName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - outputParameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
A collection of [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md) objects.  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[ExecuteStoredProcedureScalar Overload](databaseaccessor-executestoredprocedurescalar-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

