---
title: DatabaseAccessor.ExecuteStoredProcedure(T1, T2, T3) Method (String, ParameterSet, ParameterSet, Int32) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedure(T1, T2, T3) Method (String, ParameterSet, ParameterSet, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedure``3(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet,Microsoft.Dynamics.Commerce.Runtime.ParameterSet,System.Int32@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn989071(v=AX.60)
ms:contentKeyID: 65319027
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ExecuteStoredProcedure(T1, T2, T3) Method (String, ParameterSet, ParameterSet, Int32)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteStoredProcedure(Of T1 As {New, CommerceEntity}, T2 As {New, CommerceEntity}, T3 As {New, CommerceEntity}) ( _
    procedureName As String, _
    parameters As ParameterSet, _
    outputParameters As ParameterSet, _
    <OutAttribute> ByRef returnValue As Integer _
) As Tuple(Of ReadOnlyCollection(Of T1), ReadOnlyCollection(Of T2), ReadOnlyCollection(Of T3))
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim outputParameters As ParameterSet
Dim returnValue As Integer
Dim returnValue As Tuple(Of ReadOnlyCollection(Of T1), ReadOnlyCollection(Of T2), ReadOnlyCollection(Of T3))

returnValue = Me.ExecuteStoredProcedure(procedureName, _
    parameters, outputParameters, returnValue)
```

``` csharp
protected Tuple<ReadOnlyCollection<T1>, ReadOnlyCollection<T2>, ReadOnlyCollection<T3>> ExecuteStoredProcedure<T1, T2, T3>(
    string procedureName,
    ParameterSet parameters,
    ParameterSet outputParameters,
    out int returnValue
)
where T1 : new(), CommerceEntity
where T2 : new(), CommerceEntity
where T3 : new(), CommerceEntity
```

``` c++
protected:
generic<typename T1, typename T2, typename T3>
where T1 : gcnew(), CommerceEntity
where T2 : gcnew(), CommerceEntity
where T3 : gcnew(), CommerceEntity
Tuple<ReadOnlyCollection<T1>^, ReadOnlyCollection<T2>^, ReadOnlyCollection<T3>^>^ ExecuteStoredProcedure(
    String^ procedureName, 
    ParameterSet^ parameters, 
    ParameterSet^ outputParameters, 
    [OutAttribute] int% returnValue
)
```

#### Type Parameters

  - T1

<!-- end list -->

  - T2

<!-- end list -->

  - T3

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

  - returnValue  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<T1\>, [ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<T2\>, [ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<T3\>\>  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[ExecuteStoredProcedure\<T1, T2, T3\> Overload](databaseaccessor-executestoredprocedure-t1-t2-t3-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

