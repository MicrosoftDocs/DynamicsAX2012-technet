---
title: PagingInfo.Paginate(T) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Paginate(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.Paginate``1(System.Collections.Generic.ICollection{``0})
ms:mtpsurl: https://technet.microsoft.com/library/Dn989793(v=AX.60)
ms:contentKeyID: 65320250
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.Paginate``1
dev_langs:
- CSharp
- C++
- VB
---

# Paginate(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Applies paging to a list from PagingInfo.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Paginate(Of T) ( _
    unpagedCollection As ICollection(Of T) _
) As ICollection(Of T)
'Usage
Dim instance As PagingInfo
Dim unpagedCollection As ICollection(Of T)
Dim returnValue As ICollection(Of T)

returnValue = instance.Paginate(unpagedCollection)
```

``` csharp
public ICollection<T> Paginate<T>(
    ICollection<T> unpagedCollection
)
```

``` c++
public:
generic<typename T>
ICollection<T>^ Paginate(
    ICollection<T>^ unpagedCollection
)
```

#### Type Parameters

  - T

#### Parameters

  - unpagedCollection  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<T\>  

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<T\>  
The list of paged results.  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

