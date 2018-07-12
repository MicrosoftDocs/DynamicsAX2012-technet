---
title: UserAuthorizationException Constructor (String, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: UserAuthorizationException Constructor (String, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.UserAuthorizationException.#ctor(System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.userauthorizationexception.userauthorizationexception(v=AX.60)
ms:contentKeyID: 62204936
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# UserAuthorizationException Constructor (String, String, Object[])

Initializes a new instance of the [UserAuthorizationException](userauthorizationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

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

Dim instance As New UserAuthorizationException(errorResourceId, _
    message, args)
```

``` csharp
public UserAuthorizationException(
    string errorResourceId,
    string message,
    params Object[] args
)
```

``` c++
public:
UserAuthorizationException(
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

[UserAuthorizationException Class](userauthorizationexception-class-microsoft-dynamics-commerce-runtime.md)

[UserAuthorizationException Overload](userauthorizationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

