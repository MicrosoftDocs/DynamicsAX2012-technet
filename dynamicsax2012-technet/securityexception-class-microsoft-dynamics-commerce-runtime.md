---
title: SecurityException Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SecurityException Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.SecurityException
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.securityexception(v=AX.60)
ms:contentKeyID: 49823039
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SecurityException
dev_langs:
- CSharp
- C++
- VB
---

# SecurityException Class

Security exception.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Class SecurityException _
    Inherits CommerceRuntimeException
'Usage
Dim instance As SecurityException
```

``` csharp
public class SecurityException : CommerceRuntimeException
```

``` c++
public ref class SecurityException : public CommerceRuntimeException
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [System.Exception](https://technet.microsoft.com/en-us/library/c18k6c59\(v=ax.60\))  
    [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)  
      Microsoft.Dynamics.Commerce.Runtime.SecurityException  
        [Microsoft.Dynamics.Commerce.Runtime.DeviceAuthenticationException](deviceauthenticationexception-class-microsoft-dynamics-commerce-runtime.md)  
        [Microsoft.Dynamics.Commerce.Runtime.UserAuthenticationException](userauthenticationexception-class-microsoft-dynamics-commerce-runtime.md)  
        [Microsoft.Dynamics.Commerce.Runtime.UserAuthorizationException](userauthorizationexception-class-microsoft-dynamics-commerce-runtime.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

