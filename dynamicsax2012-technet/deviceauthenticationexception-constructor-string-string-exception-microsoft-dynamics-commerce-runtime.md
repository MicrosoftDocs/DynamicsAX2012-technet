---
title: DeviceAuthenticationException Constructor (String, String, Exception) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DeviceAuthenticationException Constructor (String, String, Exception)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DeviceAuthenticationException.#ctor(System.String,System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.deviceauthenticationexception.deviceauthenticationexception(v=AX.60)
ms:contentKeyID: 62202088
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DeviceAuthenticationException Constructor (String, String, Exception)

Initializes a new instance of the [DeviceAuthenticationException](deviceauthenticationexception-class-microsoft-dynamics-commerce-runtime.md) class.

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

Dim instance As New DeviceAuthenticationException(errorResourceId, _
    message, inner)
```

``` csharp
public DeviceAuthenticationException(
    string errorResourceId,
    string message,
    Exception inner
)
```

``` c++
public:
DeviceAuthenticationException(
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

[DeviceAuthenticationException Class](deviceauthenticationexception-class-microsoft-dynamics-commerce-runtime.md)

[DeviceAuthenticationException Overload](deviceauthenticationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

