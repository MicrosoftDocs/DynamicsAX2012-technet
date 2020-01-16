---
title: PagedResult(TEntity) Constructor (ReadOnlyCollection(TEntity), Boolean) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: PagedResult(TEntity) Constructor (ReadOnlyCollection(TEntity), Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.PagedResult`1.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{`0},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/Dn686367(v=AX.60)
ms:contentKeyID: 62214366
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PagedResult(TEntity) Constructor (ReadOnlyCollection(TEntity), Boolean)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    results As ReadOnlyCollection(Of TEntity), _
    hasNextPage As Boolean _
)
'Usage
Dim results As ReadOnlyCollection(Of TEntity)
Dim hasNextPage As Boolean

Dim instance As New PagedResult(results, _
    hasNextPage)
```

``` csharp
public PagedResult(
    ReadOnlyCollection<TEntity> results,
    bool hasNextPage
)
```

``` c++
public:
PagedResult(
    ReadOnlyCollection<TEntity>^ results, 
    bool hasNextPage
)
```

#### Parameters

  - results  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TEntity](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\>  

<!-- end list -->

  - hasNextPage  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[PagedResult\<TEntity\> Class](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)

[PagedResult\<TEntity\> Overload](pagedresult-tentity-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

