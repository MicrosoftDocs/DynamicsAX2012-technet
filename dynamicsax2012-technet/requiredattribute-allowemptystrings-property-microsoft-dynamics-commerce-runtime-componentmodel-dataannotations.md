---
title: RequiredAttribute.AllowEmptyStrings Property  (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: AllowEmptyStrings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RequiredAttribute.AllowEmptyStrings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.requiredattribute.allowemptystrings(v=AX.60)
ms:contentKeyID: 65322243
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.RequiredAttribute.AllowEmptyStrings
dev_langs:
- CSharp
- C++
- VB
---

# AllowEmptyStrings Property

Gets or sets a value indicating whether the attribute should allow empty strings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property AllowEmptyStrings As Boolean
    Get
    Set
'Usage
Dim instance As RequiredAttribute
Dim value As Boolean

value = instance.AllowEmptyStrings

instance.AllowEmptyStrings = value
```

``` csharp
public bool AllowEmptyStrings { get; set; }
```

``` c++
public:
property bool AllowEmptyStrings {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[RequiredAttribute Class](requiredattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

