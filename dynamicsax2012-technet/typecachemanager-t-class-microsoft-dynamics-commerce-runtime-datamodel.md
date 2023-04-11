---
title: TypeCacheManager(T) Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TypeCacheManager(T) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCacheManager`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn968592(v=AX.60)
ms:contentKeyID: 65321714
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCacheManager`1
dev_langs:
- CSharp
- C++
- VB
---

# TypeCacheManager(T) Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Manages the [EntityTypeCache](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md) classes that allows reflection on entity types to be done only once.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Class TypeCacheManager(Of T As TypeCache)
'Usage
Dim instance As TypeCacheManager(Of T)
```

``` csharp
public class TypeCacheManager<T>
where T : TypeCache
```

``` c++
generic<typename T>
where T : TypeCache
public ref class TypeCacheManager
```

#### Type Parameters

  - T

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCacheManager\<T\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

