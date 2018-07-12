---
title: CartValidationException Constructor (String, String, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CartValidationException Constructor (String, String, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CartValidationException.#ctor(System.String,System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.cartvalidationexception.cartvalidationexception(v=AX.60)
ms:contentKeyID: 62208319
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CartValidationException Constructor (String, String, String, Object[])

Initializes a new instance of the [CartValidationException](cartvalidationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    cartId As String, _
    message As String, _
    ParamArray args As Object() _
)
'Usage
Dim errorResourceId As String
Dim cartId As String
Dim message As String
Dim args As Object()

Dim instance As New CartValidationException(errorResourceId, _
    cartId, message, args)
```

``` csharp
public CartValidationException(
    string errorResourceId,
    string cartId,
    string message,
    params Object[] args
)
```

``` c++
public:
CartValidationException(
    String^ errorResourceId, 
    String^ cartId, 
    String^ message, 
    ... array<Object^>^ args
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[CartValidationException Class](cartvalidationexception-class-microsoft-dynamics-commerce-runtime.md)

[CartValidationException Overload](cartvalidationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

