---
title: RequiredAttribute Class (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: RequiredAttribute Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RequiredAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.requiredattribute(v=AX.60)
ms:contentKeyID: 65321883
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RequiredAttribute
dev_langs:
- CSharp
- C++
- VB
---

# RequiredAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Validation attribute to indicate that a property field or parameter is required.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Property, AllowMultiple := False)> _
Public Class RequiredAttribute _
    Inherits ValidationAttribute
'Usage
Dim instance As RequiredAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Property, AllowMultiple = false)]
public class RequiredAttribute : ValidationAttribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Property, AllowMultiple = false)]
public ref class RequiredAttribute : public ValidationAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute](validationattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)  
      Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RequiredAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

