---
title: CommerceRuntimeException Constructor (String, String, Exception) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CommerceRuntimeException Constructor (String, String, Exception)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException.#ctor(System.String,System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeexception.commerceruntimeexception(v=AX.60)
ms:contentKeyID: 49823504
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommerceRuntimeException Constructor (String, String, Exception)

Initializes a new instance of the [CommerceRuntimeException](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    errorResourceId As String, _
    message As String, _
    innerException As Exception _
)
'Usage
Dim errorResourceId As String
Dim message As String
Dim innerException As Exception

Dim instance As New CommerceRuntimeException(errorResourceId, _
    message, innerException)
```

``` csharp
protected CommerceRuntimeException(
    string errorResourceId,
    string message,
    Exception innerException
)
```

``` c++
protected:
CommerceRuntimeException(
    String^ errorResourceId, 
    String^ message, 
    Exception^ innerException
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - innerException  
    Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[CommerceRuntimeException Class](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)

[CommerceRuntimeException Overload](commerceruntimeexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

