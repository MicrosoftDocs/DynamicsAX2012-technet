---
title: DatabaseAccessor.ExecuteSelect(T) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteSelect(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteSelect``1(Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery)
ms:mtpsurl: https://technet.microsoft.com/library/Dn967075(v=AX.60)
ms:contentKeyID: 65318442
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ExecuteSelect``1
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteSelect(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function ExecuteSelect(Of T As {New, CommerceEntity}) ( _
    query As SqlQuery _
) As ReadOnlyCollection(Of T)
'Usage
Dim instance As DatabaseAccessor
Dim query As SqlQuery
Dim returnValue As ReadOnlyCollection(Of T)

returnValue = instance.ExecuteSelect(query)
```

``` csharp
public ReadOnlyCollection<T> ExecuteSelect<T>(
    SqlQuery query
)
where T : new(), CommerceEntity
```

``` c++
public:
generic<typename T>
where T : gcnew(), CommerceEntity
ReadOnlyCollection<T>^ ExecuteSelect(
    SqlQuery^ query
)
```

#### Type Parameters

  - T

#### Parameters

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery](sqlquery-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<T\>  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

