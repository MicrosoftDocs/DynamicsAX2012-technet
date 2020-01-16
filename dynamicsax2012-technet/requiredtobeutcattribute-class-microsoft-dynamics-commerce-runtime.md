---
title: RequiredToBeUtcAttribute Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: RequiredToBeUtcAttribute Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.RequiredToBeUtcAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requiredtobeutcattribute(v=AX.60)
ms:contentKeyID: 62206938
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequiredToBeUtcAttribute
dev_langs:
- CSharp
- C++
- VB
---

# RequiredToBeUtcAttribute Class

Annotates that a property is required to be UTC datetime offset.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Property, AllowMultiple := False)> _
Public NotInheritable Class RequiredToBeUtcAttribute _
    Inherits Attribute
'Usage
Dim instance As RequiredToBeUtcAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Property, AllowMultiple = false)]
public sealed class RequiredToBeUtcAttribute : Attribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Property, AllowMultiple = false)]
public ref class RequiredToBeUtcAttribute sealed : public Attribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    Microsoft.Dynamics.Commerce.Runtime.RequiredToBeUtcAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

