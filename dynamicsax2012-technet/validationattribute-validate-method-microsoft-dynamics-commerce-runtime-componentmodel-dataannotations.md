---
title: ValidationAttribute.Validate Method  (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: Validate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute.Validate(System.Object,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.validationattribute.validate(v=AX.60)
ms:contentKeyID: 65318153
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ValidationAttribute.Validate
dev_langs:
- CSharp
- C++
- VB
---

# Validate Method

Validate the property value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public MustOverride Function Validate ( _
    value As Object, _
    name As String _
) As ICollection(Of DataValidationFailure)
'Usage
Dim instance As ValidationAttribute
Dim value As Object
Dim name As String
Dim returnValue As ICollection(Of DataValidationFailure)

returnValue = instance.Validate(value, _
    name)
```

``` csharp
public abstract ICollection<DataValidationFailure> Validate(
    Object value,
    string name
)
```

``` c++
public:
virtual ICollection<DataValidationFailure^>^ Validate(
    Object^ value, 
    String^ name
) abstract
```

#### Parameters

  - value  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  
Validation failures.  

## See Also

#### Reference

[ValidationAttribute Class](validationattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

