---
title: TypeCacheManager(T).GetCacheInstance Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetCacheInstance Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCacheManager`1.GetCacheInstance(System.Type,System.Func{System.Type,`0})
ms:mtpsurl: https://technet.microsoft.com/library/Dn988029(v=AX.60)
ms:contentKeyID: 65316822
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCacheManager`1.GetCacheInstance
dev_langs:
- CSharp
- C++
- VB
---

# GetCacheInstance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the [EntityTypeCache](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md) for the type provided.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetCacheInstance ( _
    type As Type, _
    creator As Func(Of Type, T) _
) As T
'Usage
Dim instance As TypeCacheManager
Dim type As Type
Dim creator As Func(Of Type, T)
Dim returnValue As T

returnValue = instance.GetCacheInstance(type, _
    creator)
```

``` csharp
public T GetCacheInstance(
    Type type,
    Func<Type, T> creator
)
```

``` c++
public:
T GetCacheInstance(
    Type^ type, 
    Func<Type^, T>^ creator
)
```

#### Parameters

  - type  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

<!-- end list -->

  - creator  
    Type: [System.Func](https://technet.microsoft.com/library/bb549151\(v=ax.60\))\<[Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\)), [T](typecachemanager-t-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [T](typecachemanager-t-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The [EntityTypeCache](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md) for the type provided.  

## See Also

#### Reference

[TypeCacheManager\<T\> Class](typecachemanager-t-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

