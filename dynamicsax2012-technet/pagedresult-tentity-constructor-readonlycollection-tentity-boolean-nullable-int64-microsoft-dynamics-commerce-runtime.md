---
title: PagedResult(TEntity) Constructor (ReadOnlyCollection(TEntity), Boolean, Nullable(Int64)) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: PagedResult(TEntity) Constructor (ReadOnlyCollection(TEntity), Boolean, Nullable(Int64))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.PagedResult`1.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{`0},System.Boolean,System.Nullable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn685794(v=AX.60)
ms:contentKeyID: 62211513
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PagedResult(TEntity) Constructor (ReadOnlyCollection(TEntity), Boolean, Nullable(Int64))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    results As ReadOnlyCollection(Of TEntity), _
    hasNextPage As Boolean, _
    totalCount As Nullable(Of Long) _
)
'Usage
Dim results As ReadOnlyCollection(Of TEntity)
Dim hasNextPage As Boolean
Dim totalCount As Nullable(Of Long)

Dim instance As New PagedResult(results, _
    hasNextPage, totalCount)
```

``` csharp
public PagedResult(
    ReadOnlyCollection<TEntity> results,
    bool hasNextPage,
    Nullable<long> totalCount
)
```

``` c++
public:
PagedResult(
    ReadOnlyCollection<TEntity>^ results, 
    bool hasNextPage, 
    Nullable<long long> totalCount
)
```

#### Parameters

  - results  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[TEntity](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\>  

<!-- end list -->

  - hasNextPage  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - totalCount  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[PagedResult\<TEntity\> Class](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)

[PagedResult\<TEntity\> Overload](pagedresult-tentity-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

