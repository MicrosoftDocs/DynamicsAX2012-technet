---
title: RegularExpressionAttribute.Pattern Property  (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: Pattern Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RegularExpressionAttribute.Pattern
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.regularexpressionattribute.pattern(v=AX.60)
ms:contentKeyID: 65318949
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RegularExpressionAttribute.Pattern
dev_langs:
- CSharp
- C++
- VB
---

# Pattern Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the regular expression pattern to use.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Pattern As String
    Get
    Private Set
'Usage
Dim instance As RegularExpressionAttribute
Dim value As String

value = instance.Pattern
```

``` csharp
public string Pattern { get; private set; }
```

``` c++
public:
property String^ Pattern {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RegularExpressionAttribute Class](regularexpressionattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

