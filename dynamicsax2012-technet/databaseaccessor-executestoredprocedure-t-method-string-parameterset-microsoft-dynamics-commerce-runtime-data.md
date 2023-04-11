---
title: DatabaseAccessor.ExecuteStoredProcedure(T) Method (String, ParameterSet) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedure(T) Method (String, ParameterSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteStoredProcedure``1(System.String,Microsoft.Dynamics.Commerce.Runtime.ParameterSet)
ms:mtpsurl: https://technet.microsoft.com/library/Dn717859(v=AX.60)
ms:contentKeyID: 62209940
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ExecuteStoredProcedure(T) Method (String, ParameterSet)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the stored procedure using the specified parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function ExecuteStoredProcedure(Of T As {New, CommerceEntity}) ( _
    procedureName As String, _
    parameters As ParameterSet _
) As ReadOnlyCollection(Of T)
'Usage
Dim procedureName As String
Dim parameters As ParameterSet
Dim returnValue As ReadOnlyCollection(Of T)

returnValue = Me.ExecuteStoredProcedure(procedureName, _
    parameters)
```

``` csharp
protected ReadOnlyCollection<T> ExecuteStoredProcedure<T>(
    string procedureName,
    ParameterSet parameters
)
where T : new(), CommerceEntity
```

``` c++
protected:
generic<typename T>
where T : gcnew(), CommerceEntity
ReadOnlyCollection<T>^ ExecuteStoredProcedure(
    String^ procedureName, 
    ParameterSet^ parameters
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

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T\>  
A collection of [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md) objects.  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[ExecuteStoredProcedure\<T\> Overload](databaseaccessor-executestoredprocedure-t-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

