---
title: DatabaseAccessor.ExecuteStoredProcedure(T1, T2) Method (String, ParameterSet) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedure(T1, T2) Method (String, ParameterSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedure``2(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet)
ms:mtpsurl: https://technet.microsoft.com/library/Dn991076(v=AX.60)
ms:contentKeyID: 65322518
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ExecuteStoredProcedure(T1, T2) Method (String, ParameterSet)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteStoredProcedure(Of T1 As {New, CommerceEntity}, T2 As {New, CommerceEntity}) ( _
    procedureName As String, _
    parameters As ParameterSet _
) As Tuple(Of ReadOnlyCollection(Of T1), ReadOnlyCollection(Of T2))
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim returnValue As Tuple(Of ReadOnlyCollection(Of T1), ReadOnlyCollection(Of T2))

returnValue = Me.ExecuteStoredProcedure(procedureName, _
    parameters)
```

``` csharp
protected Tuple<ReadOnlyCollection<T1>, ReadOnlyCollection<T2>> ExecuteStoredProcedure<T1, T2>(
    string procedureName,
    ParameterSet parameters
)
where T1 : new(), CommerceEntity
where T2 : new(), CommerceEntity
```

``` c++
protected:
generic<typename T1, typename T2>
where T1 : gcnew(), CommerceEntity
where T2 : gcnew(), CommerceEntity
Tuple<ReadOnlyCollection<T1>^, ReadOnlyCollection<T2>^>^ ExecuteStoredProcedure(
    String^ procedureName, 
    ParameterSet^ parameters
)
```

#### Type Parameters

  - T1

<!-- end list -->

  - T2

#### Parameters

  - procedureName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T1\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T2\>\>  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[ExecuteStoredProcedure\<T1, T2\> Overload](databaseaccessor-executestoredprocedure-t1-t2-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

