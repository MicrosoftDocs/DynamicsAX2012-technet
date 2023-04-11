---
title: UserChangePasswordServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UserChangePasswordServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest.#ctor(System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userchangepasswordservicerequest.userchangepasswordservicerequest(v=AX.60)
ms:contentKeyID: 65320271
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UserChangePasswordServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    staffId As String, _
    authenticationProvider As String, _
    oldPassword As String, _
    newPassword As String, _
    logOnConfiguration As LogOnConfiguration, _
    changePassword As Boolean _
)
'Usage
Dim staffId As String
Dim authenticationProvider As String
Dim oldPassword As String
Dim newPassword As String
Dim logOnConfiguration As LogOnConfiguration
Dim changePassword As Boolean

Dim instance As New UserChangePasswordServiceRequest(staffId, _
    authenticationProvider, oldPassword, _
    newPassword, logOnConfiguration, _
    changePassword)
```

``` csharp
public UserChangePasswordServiceRequest(
    string staffId,
    string authenticationProvider,
    string oldPassword,
    string newPassword,
    LogOnConfiguration logOnConfiguration,
    bool changePassword
)
```

``` c++
public:
UserChangePasswordServiceRequest(
    String^ staffId, 
    String^ authenticationProvider, 
    String^ oldPassword, 
    String^ newPassword, 
    LogOnConfiguration logOnConfiguration, 
    bool changePassword
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - authenticationProvider  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - oldPassword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - newPassword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnConfiguration  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - changePassword  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[UserChangePasswordServiceRequest Class](userchangepasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

