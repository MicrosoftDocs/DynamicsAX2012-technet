---
title: CartValidationException.LineValidationResults Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: LineValidationResults Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CartValidationException.LineValidationResults
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartvalidationexception.linevalidationresults(v=AX.60)
ms:contentKeyID: 62210196
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CartValidationException.LineValidationResults
dev_langs:
- CSharp
- C++
- VB
---

# LineValidationResults Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of validation results for each cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property LineValidationResults As CartLineValidationResults
    Get
    Private Set
'Usage
Dim instance As CartValidationException
Dim value As CartLineValidationResults

value = instance.LineValidationResults
```

``` csharp
public CartLineValidationResults LineValidationResults { get; private set; }
```

``` c++
public:
property CartLineValidationResults^ LineValidationResults {
    CartLineValidationResults^ get ();
    private: void set (CartLineValidationResults^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md)  
Returns [CartLineValidationResults](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[CartValidationException Class](cartvalidationexception-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

