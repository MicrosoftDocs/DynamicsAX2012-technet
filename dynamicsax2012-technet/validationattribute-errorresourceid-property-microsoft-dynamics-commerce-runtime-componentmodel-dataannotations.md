---
title: ValidationAttribute.ErrorResourceId Property  (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: ErrorResourceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute.ErrorResourceId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.validationattribute.errorresourceid(v=AX.60)
ms:contentKeyID: 65315903
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute.ErrorResourceId
dev_langs:
- CSharp
- C++
- VB
---

# ErrorResourceId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets and explicit error message string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ErrorResourceId As String
    Get
    Set
'Usage
Dim instance As ValidationAttribute
Dim value As String

value = instance.ErrorResourceId

instance.ErrorResourceId = value
```

``` csharp
public string ErrorResourceId { get; set; }
```

``` c++
public:
property String^ ErrorResourceId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ValidationAttribute Class](validationattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

