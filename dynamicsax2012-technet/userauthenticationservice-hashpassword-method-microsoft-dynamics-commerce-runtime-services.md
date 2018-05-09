---
title: UserAuthenticationService.HashPassword Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: HashPassword Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService.HashPassword(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.userauthenticationservice.hashpassword(v=AX.60)
ms:contentKeyID: 65319616
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService.HashPassword
dev_langs:
- CSharp
- C++
- VB
---

# HashPassword Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function HashPassword ( _
    context As RequestContext, _
    password As String, _
    algorithm As String, _
    staffId As String _
) As String
'Usage
Dim context As RequestContext
Dim password As String
Dim algorithm As String
Dim staffId As String
Dim returnValue As String

returnValue = UserAuthenticationService.HashPassword(context, _
    password, algorithm, staffId)
```

``` csharp
public static string HashPassword(
    RequestContext context,
    string password,
    string algorithm,
    string staffId
)
```

``` c++
public:
static String^ HashPassword(
    RequestContext^ context, 
    String^ password, 
    String^ algorithm, 
    String^ staffId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - password  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - algorithm  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[UserAuthenticationService Class](userauthenticationservice-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

