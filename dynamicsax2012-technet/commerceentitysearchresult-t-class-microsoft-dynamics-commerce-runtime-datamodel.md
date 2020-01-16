---
title: CommerceEntitySearchResult(T) Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CommerceEntitySearchResult(T) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearchResult`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn686186(v=AX.60)
ms:contentKeyID: 62213425
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearchResult`1
dev_langs:
- CSharp
- C++
- VB
---

# CommerceEntitySearchResult(T) Class

Base class for search result.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class CommerceEntitySearchResult(Of T As CommerceEntity) _
    Inherits CommerceEntitySearch
'Usage
Dim instance As CommerceEntitySearchResult(Of T)
```

``` csharp
public abstract class CommerceEntitySearchResult<T> : CommerceEntitySearch
where T : CommerceEntity
```

``` c++
generic<typename T>
where T : CommerceEntity
public ref class CommerceEntitySearchResult abstract : public CommerceEntitySearch
```

#### Type Parameters

  - T

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearch](commerceentitysearch-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearchResult\<T\>  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

