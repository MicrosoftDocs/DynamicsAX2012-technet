---
title: PagingInfo.GetPageFromCollections(T, TKey) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetPageFromCollections(T, TKey) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.GetPageFromCollections``2(System.Func{``0,``1},System.Collections.Generic.ICollection{``0}[])
ms:mtpsurl: https://technet.microsoft.com/library/Dn998795(v=AX.60)
ms:contentKeyID: 65317478
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.GetPageFromCollections``2
dev_langs:
- CSharp
- C++
- VB
---

# GetPageFromCollections(T, TKey) Method

Gets a page from collections based on current pagination info.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetPageFromCollections(Of T As Class, TKey) ( _
    orderByKey As Func(Of T, TKey), _
    ParamArray collections As ICollection(Of T)() _
) As PagedResult(Of T)
'Usage
Dim instance As PagingInfo
Dim orderByKey As Func(Of T, TKey)
Dim collections As ICollection(Of T)()
Dim returnValue As PagedResult(Of T)

returnValue = instance.GetPageFromCollections(orderByKey, _
    collections)
```

``` csharp
public PagedResult<T> GetPageFromCollections<T, TKey>(
    Func<T, TKey> orderByKey,
    params ICollection<T>[] collections
)
where T : class
```

``` c++
public:
generic<typename T, typename TKey>
where T : ref class
PagedResult<T>^ GetPageFromCollections(
    Func<T, TKey>^ orderByKey, 
    ... array<ICollection<T>^>^ collections
)
```

#### Type Parameters

  - T

<!-- end list -->

  - TKey

#### Parameters

  - orderByKey  
    Type: [System.Func](https://technet.microsoft.com/library/bb549151\(v=ax.60\))\<T, TKey\>  

<!-- end list -->

  - collections  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<T\>\[\]  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<T\>  
The paged result.  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

