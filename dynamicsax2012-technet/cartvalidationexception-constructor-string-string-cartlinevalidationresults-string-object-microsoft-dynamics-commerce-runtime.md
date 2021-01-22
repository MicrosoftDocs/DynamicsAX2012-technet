---
title: CartValidationException Constructor (String, String, CartLineValidationResults, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CartValidationException Constructor (String, String, CartLineValidationResults, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CartValidationException.#ctor(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartvalidationexception.cartvalidationexception(v=AX.60)
ms:contentKeyID: 62213758
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CartValidationException Constructor (String, String, CartLineValidationResults, String, Object[])

Initializes a new instance of the [CartValidationException](cartvalidationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    cartId As String, _
    cartLineValidationResults As CartLineValidationResults, _
    message As String, _
    ParamArray args As Object() _
)
'Usage
Dim errorResourceId As String
Dim cartId As String
Dim cartLineValidationResults As CartLineValidationResults
Dim message As String
Dim args As Object()

Dim instance As New CartValidationException(errorResourceId, _
    cartId, cartLineValidationResults, _
    message, args)
```

``` csharp
public CartValidationException(
    string errorResourceId,
    string cartId,
    CartLineValidationResults cartLineValidationResults,
    string message,
    params Object[] args
)
```

``` c++
public:
CartValidationException(
    String^ errorResourceId, 
    String^ cartId, 
    CartLineValidationResults^ cartLineValidationResults, 
    String^ message, 
    ... array<Object^>^ args
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartLineValidationResults  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[CartValidationException Class](cartvalidationexception-class-microsoft-dynamics-commerce-runtime.md)

[CartValidationException Overload](cartvalidationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

