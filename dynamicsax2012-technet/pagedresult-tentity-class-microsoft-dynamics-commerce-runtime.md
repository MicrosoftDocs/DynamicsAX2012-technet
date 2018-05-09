---
title: PagedResult(TEntity) Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: PagedResult(TEntity) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.PagedResult`1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn740143(v=AX.60)
ms:contentKeyID: 62214959
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.PagedResult`1
dev_langs:
- CSharp
- C++
- VB
---

# PagedResult(TEntity) Class

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class PagedResult(Of TEntity As Class)
'Usage
Dim instance As PagedResult(Of TEntity)
```

``` csharp
[DataContractAttribute]
public sealed class PagedResult<TEntity>
where TEntity : class
```

``` c++
[DataContractAttribute]
generic<typename TEntity>
where TEntity : ref class
public ref class PagedResult sealed
```

#### Type Parameters

  - TEntity

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.PagedResult\<TEntity\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

