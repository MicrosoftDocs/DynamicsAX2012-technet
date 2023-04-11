---
title: DefaultSortOrderAttribute Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DefaultSortOrderAttribute Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DefaultSortOrderAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.defaultsortorderattribute(v=AX.60)
ms:contentKeyID: 62210079
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DefaultSortOrderAttribute
dev_langs:
- CSharp
- C++
- VB
---

# DefaultSortOrderAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This class defines an attribute that can be applied to commerce entity classs to define default sort order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Class, Inherited := True, AllowMultiple := True)> _
Public NotInheritable Class DefaultSortOrderAttribute _
    Inherits Attribute
'Usage
Dim instance As DefaultSortOrderAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Class, Inherited = true, AllowMultiple = true)]
public sealed class DefaultSortOrderAttribute : Attribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Class, Inherited = true, AllowMultiple = true)]
public ref class DefaultSortOrderAttribute sealed : public Attribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    Microsoft.Dynamics.Commerce.Runtime.DefaultSortOrderAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

