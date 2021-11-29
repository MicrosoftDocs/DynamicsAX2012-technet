---
title: ValidationAttribute Constructor  (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: ValidationAttribute Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute.#ctor(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.validationattribute.validationattribute(v=AX.60)
ms:contentKeyID: 65322327
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ValidationAttribute Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ValidationAttribute](validationattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    errorResourceId As String _
)
'Usage
Dim errorResourceId As String

Dim instance As New ValidationAttribute(errorResourceId)
```

``` csharp
protected ValidationAttribute(
    string errorResourceId
)
```

``` c++
protected:
ValidationAttribute(
    String^ errorResourceId
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ValidationAttribute Class](validationattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

