---
title: CartLineValidationResults.HasErrors Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: HasErrors Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.HasErrors
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartlinevalidationresults.haserrors(v=AX.60)
ms:contentKeyID: 62208925
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.HasErrors
dev_langs:
- CSharp
- C++
- VB
---

# HasErrors Property

Gets a value indicating whether there are any errors in the validation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property HasErrors As Boolean
    Get
'Usage
Dim instance As CartLineValidationResults
Dim value As Boolean

value = instance.HasErrors
```

``` csharp
public bool HasErrors { get; }
```

``` c++
public:
property bool HasErrors {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CartLineValidationResults Class](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

