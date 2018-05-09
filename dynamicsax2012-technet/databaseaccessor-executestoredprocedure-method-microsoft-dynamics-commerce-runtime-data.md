---
title: DatabaseAccessor.ExecuteStoredProcedure Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedure Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedure(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet,Microsoft.Dynamics.Commerce.Runtime.ParameterSet,System.Action{Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult},Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager,System.Int32@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.databaseaccessor.executestoredprocedure(v=AX.60)
ms:contentKeyID: 65321962
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedure
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteStoredProcedure Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub ExecuteStoredProcedure ( _
    procedureName As String, _
    parameters As ParameterSet, _
    outputParameters As ParameterSet, _
    resultCallback As Action(Of IDatabaseResult), _
    connectionManager As ConnectionManager, _
    <OutAttribute> ByRef returnValue As Integer _
)
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim outputParameters As ParameterSet
Dim resultCallback As Action(Of IDatabaseResult)
Dim connectionManager As ConnectionManager
Dim returnValue As Integer

Me.ExecuteStoredProcedure(procedureName, _
    parameters, outputParameters, resultCallback, _
    connectionManager, returnValue)
```

``` csharp
protected void ExecuteStoredProcedure(
    string procedureName,
    ParameterSet parameters,
    ParameterSet outputParameters,
    Action<IDatabaseResult> resultCallback,
    ConnectionManager connectionManager,
    out int returnValue
)
```

``` c++
protected:
void ExecuteStoredProcedure(
    String^ procedureName, 
    ParameterSet^ parameters, 
    ParameterSet^ outputParameters, 
    Action<IDatabaseResult^>^ resultCallback, 
    ConnectionManager^ connectionManager, 
    [OutAttribute] int% returnValue
)
```

#### Parameters

  - procedureName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - outputParameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - resultCallback  
    Type: [System.Action](https://technet.microsoft.com/en-us/library/018hxwa8\(v=ax.60\))\<[IDatabaseResult](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)\>  

<!-- end list -->

  - connectionManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - returnValue  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

