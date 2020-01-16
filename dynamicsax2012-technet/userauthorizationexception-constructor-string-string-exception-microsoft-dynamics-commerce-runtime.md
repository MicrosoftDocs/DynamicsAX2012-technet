---
title: UserAuthorizationException Constructor (String, String, Exception) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: UserAuthorizationException Constructor (String, String, Exception)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.UserAuthorizationException.#ctor(System.String,System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.userauthorizationexception.userauthorizationexception(v=AX.60)
ms:contentKeyID: 62211618
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# UserAuthorizationException Constructor (String, String, Exception)

Initializes a new instance of the [UserAuthorizationException](userauthorizationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    message As String, _
    inner As Exception _
)
'Usage
Dim errorResourceId As String
Dim message As String
Dim inner As Exception

Dim instance As New UserAuthorizationException(errorResourceId, _
    message, inner)
```

``` csharp
public UserAuthorizationException(
    string errorResourceId,
    string message,
    Exception inner
)
```

``` c++
public:
UserAuthorizationException(
    String^ errorResourceId, 
    String^ message, 
    Exception^ inner
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inner  
    Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[UserAuthorizationException Class](userauthorizationexception-class-microsoft-dynamics-commerce-runtime.md)

[UserAuthorizationException Overload](userauthorizationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

