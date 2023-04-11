---
title: DatabaseAccessor.ExecuteStoredProcedure(T1, T2, T3, T4, T5, T6, T7, T8) Method (String, ParameterSet) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedure(T1, T2, T3, T4, T5, T6, T7, T8) Method (String, ParameterSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedure``8(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet)
ms:mtpsurl: https://technet.microsoft.com/library/Dn998921(v=AX.60)
ms:contentKeyID: 65317595
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ExecuteStoredProcedure(T1, T2, T3, T4, T5, T6, T7, T8) Method (String, ParameterSet)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteStoredProcedure(Of T1 As {New, CommerceEntity}, T2 As {New, CommerceEntity}, T3 As {New, CommerceEntity}, T4 As {New, CommerceEntity}, T5 As {New, CommerceEntity}, T6 As {New, CommerceEntity}, T7 As {New, CommerceEntity}, T8 As {New, CommerceEntity}) ( _
    procedureName As String, _
    parameters As ParameterSet _
) As Tuple(Of ReadOnlyCollection(Of T1), ReadOnlyCollection(Of T2), ReadOnlyCollection(Of T3), ReadOnlyCollection(Of T4), ReadOnlyCollection(Of T5), ReadOnlyCollection(Of T6), ReadOnlyCollection(Of T7), Tuple(Of ReadOnlyCollection(Of T8)))
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim returnValue As Tuple(Of ReadOnlyCollection(Of T1), ReadOnlyCollection(Of T2), ReadOnlyCollection(Of T3), ReadOnlyCollection(Of T4), ReadOnlyCollection(Of T5), ReadOnlyCollection(Of T6), ReadOnlyCollection(Of T7), Tuple(Of ReadOnlyCollection(Of T8)))

returnValue = Me.ExecuteStoredProcedure(procedureName, _
    parameters)
```

``` csharp
protected Tuple<ReadOnlyCollection<T1>, ReadOnlyCollection<T2>, ReadOnlyCollection<T3>, ReadOnlyCollection<T4>, ReadOnlyCollection<T5>, ReadOnlyCollection<T6>, ReadOnlyCollection<T7>, Tuple<ReadOnlyCollection<T8>>> ExecuteStoredProcedure<T1, T2, T3, T4, T5, T6, T7, T8>(
    string procedureName,
    ParameterSet parameters
)
where T1 : new(), CommerceEntity
where T2 : new(), CommerceEntity
where T3 : new(), CommerceEntity
where T4 : new(), CommerceEntity
where T5 : new(), CommerceEntity
where T6 : new(), CommerceEntity
where T7 : new(), CommerceEntity
where T8 : new(), CommerceEntity
```

``` c++
protected:
generic<typename T1, typename T2, typename T3, typename T4, typename T5, typename T6, typename T7, typename T8>
where T1 : gcnew(), CommerceEntity
where T2 : gcnew(), CommerceEntity
where T3 : gcnew(), CommerceEntity
where T4 : gcnew(), CommerceEntity
where T5 : gcnew(), CommerceEntity
where T6 : gcnew(), CommerceEntity
where T7 : gcnew(), CommerceEntity
where T8 : gcnew(), CommerceEntity
Tuple<ReadOnlyCollection<T1>^, ReadOnlyCollection<T2>^, ReadOnlyCollection<T3>^, ReadOnlyCollection<T4>^, ReadOnlyCollection<T5>^, ReadOnlyCollection<T6>^, ReadOnlyCollection<T7>^, Tuple<ReadOnlyCollection<T8>^>^>^ ExecuteStoredProcedure(
    String^ procedureName, 
    ParameterSet^ parameters
)
```

#### Type Parameters

  - T1

<!-- end list -->

  - T2

<!-- end list -->

  - T3

<!-- end list -->

  - T4

<!-- end list -->

  - T5

<!-- end list -->

  - T6

<!-- end list -->

  - T7

<!-- end list -->

  - T8

#### Parameters

  - procedureName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T1\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T2\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T3\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T4\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T5\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T6\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T7\>, Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T8\>\>\>  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[ExecuteStoredProcedure\<T1, T2, T3, T4, T5, T6, T7, T8\> Overload](databaseaccessor-executestoredprocedure-t1-t2-t3-t4-t5-t6-t7-t8-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

