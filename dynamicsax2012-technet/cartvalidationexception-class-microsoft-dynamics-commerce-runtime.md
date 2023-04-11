---
title: CartValidationException Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CartValidationException Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.CartValidationException
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartvalidationexception(v=AX.60)
ms:contentKeyID: 62213042
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CartValidationException
dev_langs:
- CSharp
- C++
- VB
---

# CartValidationException Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

CartValidationException class is used to indicate invalid data passed to a cart opertion.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Class CartValidationException _
    Inherits DataValidationException
'Usage
Dim instance As CartValidationException
```

``` csharp
public class CartValidationException : DataValidationException
```

``` c++
public ref class CartValidationException : public DataValidationException
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  
    [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataValidationException](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md)  
        Microsoft.Dynamics.Commerce.Runtime.CartValidationException  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

