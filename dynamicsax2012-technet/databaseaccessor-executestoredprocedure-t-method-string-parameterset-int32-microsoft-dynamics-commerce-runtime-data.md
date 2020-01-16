---
title: DatabaseAccessor.ExecuteStoredProcedure(T) Method (String, ParameterSet, Int32) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedure(T) Method (String, ParameterSet, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedure``1(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet,System.Int32@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn737634(v=AX.60)
ms:contentKeyID: 62202344
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ExecuteStoredProcedure(T) Method (String, ParameterSet, Int32)

Executes the stored procedure using the specified parameters and returns the return value of the stored procedure as an integer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteStoredProcedure(Of T As {New, CommerceEntity}) ( _
    procedureName As String, _
    parameters As ParameterSet, _
    <OutAttribute> ByRef returnValue As Integer _
) As ReadOnlyCollection(Of T)
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim returnValue As Integer
Dim returnValue As ReadOnlyCollection(Of T)

returnValue = Me.ExecuteStoredProcedure(procedureName, _
    parameters, returnValue)
```

``` csharp
protected ReadOnlyCollection<T> ExecuteStoredProcedure<T>(
    string procedureName,
    ParameterSet parameters,
    out int returnValue
)
where T : new(), CommerceEntity
```

``` c++
protected:
generic<typename T>
where T : gcnew(), CommerceEntity
ReadOnlyCollection<T>^ ExecuteStoredProcedure(
    String^ procedureName, 
    ParameterSet^ parameters, 
    [OutAttribute] int% returnValue
)
```

#### Type Parameters

  - T

#### Parameters

  - procedureName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - returnValue  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T\>  
A collection of [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md) objects.  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[ExecuteStoredProcedure\<T\> Overload](databaseaccessor-executestoredprocedure-t-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

