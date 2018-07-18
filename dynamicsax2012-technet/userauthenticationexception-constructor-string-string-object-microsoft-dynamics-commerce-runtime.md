﻿---
title: UserAuthenticationException Constructor (String, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: UserAuthenticationException Constructor (String, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.UserAuthenticationException.#ctor(System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.userauthenticationexception.userauthenticationexception(v=AX.60)
ms:contentKeyID: 62208879
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# UserAuthenticationException Constructor (String, String, Object[])

Initializes a new instance of the [UserAuthenticationException](userauthenticationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    message As String, _
    ParamArray args As Object() _
)
'Usage
Dim errorResourceId As String
Dim message As String
Dim args As Object()

Dim instance As New UserAuthenticationException(errorResourceId, _
    message, args)
```

``` csharp
public UserAuthenticationException(
    string errorResourceId,
    string message,
    params Object[] args
)
```

``` c++
public:
UserAuthenticationException(
    String^ errorResourceId, 
    String^ message, 
    ... array<Object^>^ args
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[UserAuthenticationException Class](userauthenticationexception-class-microsoft-dynamics-commerce-runtime.md)

[UserAuthenticationException Overload](userauthenticationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

