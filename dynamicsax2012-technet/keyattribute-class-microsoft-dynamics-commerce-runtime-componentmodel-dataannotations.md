---
title: KeyAttribute Class (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: KeyAttribute Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.KeyAttribute
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.keyattribute(v=AX.60)
ms:contentKeyID: 65323200
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.KeyAttribute
dev_langs:
- CSharp
- C++
- VB
---

# KeyAttribute Class

Used to mark one or more entity properties that provide the entity's unique identity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Property Or AttributeTargets.Field, AllowMultiple := False,  _
    Inherited := True)> _
Public NotInheritable Class KeyAttribute _
    Inherits Attribute
'Usage
Dim instance As KeyAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Property|AttributeTargets.Field, AllowMultiple = false, 
    Inherited = true)]
public sealed class KeyAttribute : Attribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Property|AttributeTargets::Field, AllowMultiple = false, 
    Inherited = true)]
public ref class KeyAttribute sealed : public Attribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/en-us/library/e8kc3626\(v=ax.60\))  
    Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.KeyAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

