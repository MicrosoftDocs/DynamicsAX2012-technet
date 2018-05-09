---
title: SecurityException Constructor (String, String, Exception) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SecurityException Constructor (String, String, Exception)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SecurityException.#ctor(System.String,System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.securityexception.securityexception(v=AX.60)
ms:contentKeyID: 49854446
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SecurityException Constructor (String, String, Exception)

Initializes a new instance of the [SecurityException](securityexception-class-microsoft-dynamics-commerce-runtime.md) class.

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

Dim instance As New SecurityException(errorResourceId, _
    message, inner)
```

``` csharp
public SecurityException(
    string errorResourceId,
    string message,
    Exception inner
)
```

``` c++
public:
SecurityException(
    String^ errorResourceId, 
    String^ message, 
    Exception^ inner
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inner  
    Type: [System.Exception](https://technet.microsoft.com/en-us/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[SecurityException Class](securityexception-class-microsoft-dynamics-commerce-runtime.md)

[SecurityException Overload](securityexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

