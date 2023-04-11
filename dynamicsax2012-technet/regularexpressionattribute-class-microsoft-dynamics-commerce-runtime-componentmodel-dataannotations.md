---
title: RegularExpressionAttribute Class (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: RegularExpressionAttribute Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RegularExpressionAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.regularexpressionattribute(v=AX.60)
ms:contentKeyID: 65321675
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RegularExpressionAttribute
dev_langs:
- CSharp
- C++
- VB
---

# RegularExpressionAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Regular expression validation attribute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Property, AllowMultiple := False)> _
Public Class RegularExpressionAttribute _
    Inherits ValidationAttribute
'Usage
Dim instance As RegularExpressionAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Property, AllowMultiple = false)]
public class RegularExpressionAttribute : ValidationAttribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Property, AllowMultiple = false)]
public ref class RegularExpressionAttribute : public ValidationAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute](validationattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)  
      Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RegularExpressionAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

