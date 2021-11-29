---
title: DatabaseContext.ReadEntity(T) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ReadEntity(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ReadEntity``1(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery)
ms:mtpsurl: https://technet.microsoft.com/library/Dn989094(v=AX.60)
ms:contentKeyID: 65319050
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ReadEntity``1
dev_langs:
- CSharp
- C++
- VB
---

# ReadEntity(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Reads an entity from the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Function ReadEntity(Of T As {New, CommerceEntity}) ( _
    query As IDatabaseQuery _
) As ReadOnlyCollection(Of T)
'Usage
Dim instance As DatabaseContext
Dim query As IDatabaseQuery
Dim returnValue As ReadOnlyCollection(Of T)

returnValue = instance.ReadEntity(query)
```

``` csharp
public ReadOnlyCollection<T> ReadEntity<T>(
    IDatabaseQuery query
)
where T : new(), CommerceEntity
```

``` c++
public:
generic<typename T>
where T : gcnew(), CommerceEntity
ReadOnlyCollection<T>^ ReadEntity(
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
The collection of entities read.  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

