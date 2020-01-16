---
title: DataValidationFailure.ErrorContext Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ErrorContext Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure.ErrorContext
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datavalidationfailure.errorcontext(v=AX.60)
ms:contentKeyID: 49820759
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure.ErrorContext
dev_langs:
- CSharp
- C++
- VB
---

# ErrorContext Property

Gets or sets context information on the error used for logging.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ErrorContext As String
    Get
    Set
'Usage
Dim instance As DataValidationFailure
Dim value As String

value = instance.ErrorContext

instance.ErrorContext = value
```

``` csharp
public string ErrorContext { get; set; }
```

``` c++
public:
property String^ ErrorContext {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DataValidationFailure Class](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

