---
title: ColumnAttribute Class (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: ColumnAttribute Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.columnattribute(v=AX.60)
ms:contentKeyID: 65317735
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute
dev_langs:
- CSharp
- C++
- VB
---

# ColumnAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Property Or AttributeTargets.Field, AllowMultiple := False)> _
Public Class ColumnAttribute _
    Inherits Attribute
'Usage
Dim instance As ColumnAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Property|AttributeTargets.Field, AllowMultiple = false)]
public class ColumnAttribute : Attribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Property|AttributeTargets::Field, AllowMultiple = false)]
public ref class ColumnAttribute : public Attribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

