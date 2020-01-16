---
title: ValidationAttribute.GetValidationFailure Method  (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: GetValidationFailure Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute.GetValidationFailure(System.Object,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.validationattribute.getvalidationfailure(v=AX.60)
ms:contentKeyID: 65322934
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute.GetValidationFailure
dev_langs:
- CSharp
- C++
- VB
---

# GetValidationFailure Method

Generate [DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md) object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetValidationFailure ( _
    value As Object, _
    name As String _
) As DataValidationFailure
'Usage
Dim instance As ValidationAttribute
Dim value As Object
Dim name As String
Dim returnValue As DataValidationFailure

returnValue = instance.GetValidationFailure(value, _
    name)
```

``` csharp
public virtual DataValidationFailure GetValidationFailure(
    Object value,
    string name
)
```

``` c++
public:
virtual DataValidationFailure^ GetValidationFailure(
    Object^ value, 
    String^ name
)
```

#### Parameters

  - value  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)  
Instance of [DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[ValidationAttribute Class](validationattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

