---
title: RegularExpressionAttribute.Validate Method  (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: Validate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RegularExpressionAttribute.Validate(System.Object,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.regularexpressionattribute.validate(v=AX.60)
ms:contentKeyID: 65320874
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RegularExpressionAttribute.Validate
dev_langs:
- CSharp
- C++
- VB
---

# Validate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Validate the property value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Validate ( _
    value As Object, _
    name As String _
) As ICollection(Of DataValidationFailure)
'Usage
Dim instance As RegularExpressionAttribute
Dim value As Object
Dim name As String
Dim returnValue As ICollection(Of DataValidationFailure)

returnValue = instance.Validate(value, _
    name)
```

``` csharp
public override ICollection<DataValidationFailure> Validate(
    Object value,
    string name
)
```

``` c++
public:
virtual ICollection<DataValidationFailure^>^ Validate(
    Object^ value, 
    String^ name
) override
```

#### Parameters

  - value  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  
Collection of validation failures.  

## Remarks

This override performs the specific regular expression matching of the given value.

## See Also

#### Reference

[RegularExpressionAttribute Class](regularexpressionattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

