---
title: UserAuthenticationException Constructor (String, String, Exception) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: UserAuthenticationException Constructor (String, String, Exception)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.UserAuthenticationException.#ctor(System.String,System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.userauthenticationexception.userauthenticationexception(v=AX.60)
ms:contentKeyID: 62212699
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# UserAuthenticationException Constructor (String, String, Exception)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [UserAuthenticationException](userauthenticationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

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

Dim instance As New UserAuthenticationException(errorResourceId, _
    message, inner)
```

``` csharp
public UserAuthenticationException(
    string errorResourceId,
    string message,
    Exception inner
)
```

``` c++
public:
UserAuthenticationException(
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

[UserAuthenticationException Class](userauthenticationexception-class-microsoft-dynamics-commerce-runtime.md)

[UserAuthenticationException Overload](userauthenticationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

