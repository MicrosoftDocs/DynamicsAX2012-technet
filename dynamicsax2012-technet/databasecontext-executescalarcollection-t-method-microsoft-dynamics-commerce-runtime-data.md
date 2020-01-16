---
title: DatabaseContext.ExecuteScalarCollection(T) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteScalarCollection(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ExecuteScalarCollection``1(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery)
ms:mtpsurl: https://technet.microsoft.com/library/Dn967834(v=AX.60)
ms:contentKeyID: 65319694
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ExecuteScalarCollection``1
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteScalarCollection(T) Method

Executes a query that returns a collection of single results.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Function ExecuteScalarCollection(Of T) ( _
    query As IDatabaseQuery _
) As ReadOnlyCollection(Of T)
'Usage
Dim instance As DatabaseContext
Dim query As IDatabaseQuery
Dim returnValue As ReadOnlyCollection(Of T)

returnValue = instance.ExecuteScalarCollection(query)
```

``` csharp
public ReadOnlyCollection<T> ExecuteScalarCollection<T>(
    IDatabaseQuery query
)
```

``` c++
public:
generic<typename T>
ReadOnlyCollection<T>^ ExecuteScalarCollection(
    IDatabaseQuery^ query
)
```

#### Type Parameters

  - T

#### Parameters

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery](idatabasequery-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T\>  
The scalar collection result.  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

