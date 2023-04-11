---
title: UserAuthenticationException Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: UserAuthenticationException Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.UserAuthenticationException
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.userauthenticationexception(v=AX.60)
ms:contentKeyID: 62206199
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.UserAuthenticationException
dev_langs:
- CSharp
- C++
- VB
---

# UserAuthenticationException Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Thrown when a user authentication error occurs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Class UserAuthenticationException _
    Inherits SecurityException
'Usage
Dim instance As UserAuthenticationException
```

``` csharp
public class UserAuthenticationException : SecurityException
```

``` c++
public ref class UserAuthenticationException : public SecurityException
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  
    [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.SecurityException](securityexception-class-microsoft-dynamics-commerce-runtime.md)  
        Microsoft.Dynamics.Commerce.Runtime.UserAuthenticationException  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

