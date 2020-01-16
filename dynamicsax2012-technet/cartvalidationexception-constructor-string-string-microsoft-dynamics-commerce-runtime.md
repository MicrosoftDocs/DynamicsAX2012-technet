---
title: CartValidationException Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CartValidationException Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CartValidationException.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartvalidationexception.cartvalidationexception(v=AX.60)
ms:contentKeyID: 62210679
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CartValidationException Constructor (String, String)

Initializes a new instance of the [CartValidationException](cartvalidationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    cartId As String _
)
'Usage
Dim errorResourceId As String
Dim cartId As String

Dim instance As New CartValidationException(errorResourceId, _
    cartId)
```

``` csharp
public CartValidationException(
    string errorResourceId,
    string cartId
)
```

``` c++
public:
CartValidationException(
    String^ errorResourceId, 
    String^ cartId
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CartValidationException Class](cartvalidationexception-class-microsoft-dynamics-commerce-runtime.md)

[CartValidationException Overload](cartvalidationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

