---
title: DeviceAuthenticationException Constructor (String, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DeviceAuthenticationException Constructor (String, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DeviceAuthenticationException.#ctor(System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.deviceauthenticationexception.deviceauthenticationexception(v=AX.60)
ms:contentKeyID: 62212401
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DeviceAuthenticationException Constructor (String, String, Object[])


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [DeviceAuthenticationException](deviceauthenticationexception-class-microsoft-dynamics-commerce-runtime.md) class.

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

Dim instance As New DeviceAuthenticationException(errorResourceId, _
    message, args)
```

``` csharp
public DeviceAuthenticationException(
    string errorResourceId,
    string message,
    params Object[] args
)
```

``` c++
public:
DeviceAuthenticationException(
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

[DeviceAuthenticationException Class](deviceauthenticationexception-class-microsoft-dynamics-commerce-runtime.md)

[DeviceAuthenticationException Overload](deviceauthenticationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

