---
title: CommerceRuntimeException Constructor (String, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CommerceRuntimeException Constructor (String, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException.#ctor(System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeexception.commerceruntimeexception(v=AX.60)
ms:contentKeyID: 49838278
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommerceRuntimeException Constructor (String, String, Object[])

Initializes a new instance of the [CommerceRuntimeException](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    errorResourceId As String, _
    message As String, _
    ParamArray args As Object() _
)
'Usage
Dim errorResourceId As String
Dim message As String
Dim args As Object()

Dim instance As New CommerceRuntimeException(errorResourceId, _
    message, args)
```

``` csharp
protected CommerceRuntimeException(
    string errorResourceId,
    string message,
    params Object[] args
)
```

``` c++
protected:
CommerceRuntimeException(
    String^ errorResourceId, 
    String^ message, 
    ... array<Object^>^ args
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[CommerceRuntimeException Class](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)

[CommerceRuntimeException Overload](commerceruntimeexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

