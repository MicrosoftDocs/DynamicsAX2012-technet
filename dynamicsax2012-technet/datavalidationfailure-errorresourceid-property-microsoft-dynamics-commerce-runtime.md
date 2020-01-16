---
title: DataValidationFailure.ErrorResourceId Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ErrorResourceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure.ErrorResourceId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datavalidationfailure.errorresourceid(v=AX.60)
ms:contentKeyID: 49848707
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure.ErrorResourceId
dev_langs:
- CSharp
- C++
- VB
---

# ErrorResourceId Property

Gets the error resource id indicating the cause of the validation failure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ErrorResourceId As String
    Get
    Private Set
'Usage
Dim instance As DataValidationFailure
Dim value As String

value = instance.ErrorResourceId
```

``` csharp
public string ErrorResourceId { get; private set; }
```

``` c++
public:
property String^ ErrorResourceId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DataValidationFailure Class](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

