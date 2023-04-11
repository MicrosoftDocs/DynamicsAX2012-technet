---
title: UserResetPasswordServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UserResetPasswordServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest.#ctor(System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userresetpasswordservicerequest.userresetpasswordservicerequest(v=AX.60)
ms:contentKeyID: 65321689
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UserResetPasswordServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    requestedByUserId As String, _
    targetUserId As String, _
    newPassword As String, _
    authenticationProvider As String, _
    logOnConfiguration As LogOnConfiguration, _
    changePassword As Boolean _
)
'Usage
Dim requestedByUserId As String
Dim targetUserId As String
Dim newPassword As String
Dim authenticationProvider As String
Dim logOnConfiguration As LogOnConfiguration
Dim changePassword As Boolean

Dim instance As New UserResetPasswordServiceRequest(requestedByUserId, _
    targetUserId, newPassword, authenticationProvider, _
    logOnConfiguration, changePassword)
```

``` csharp
public UserResetPasswordServiceRequest(
    string requestedByUserId,
    string targetUserId,
    string newPassword,
    string authenticationProvider,
    LogOnConfiguration logOnConfiguration,
    bool changePassword
)
```

``` c++
public:
UserResetPasswordServiceRequest(
    String^ requestedByUserId, 
    String^ targetUserId, 
    String^ newPassword, 
    String^ authenticationProvider, 
    LogOnConfiguration logOnConfiguration, 
    bool changePassword
)
```

#### Parameters

  - requestedByUserId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - targetUserId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - newPassword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - authenticationProvider  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnConfiguration  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - changePassword  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[UserResetPasswordServiceRequest Class](userresetpasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

