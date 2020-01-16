---
title: UserChangePasswordServiceRequest.ChangePassword Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ChangePassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest.ChangePassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userchangepasswordservicerequest.changepassword(v=AX.60)
ms:contentKeyID: 62212366
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest.ChangePassword
dev_langs:
- CSharp
- C++
- VB
---

# ChangePassword Property

Gets or sets a value indicating whether to force the user change password or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChangePassword As Boolean
    Get
    Set
'Usage
Dim instance As UserChangePasswordServiceRequest
Dim value As Boolean

value = instance.ChangePassword

instance.ChangePassword = value
```

``` csharp
[DataMemberAttribute]
public bool ChangePassword { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool ChangePassword {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The change password parameter.  

## See Also

#### Reference

[UserChangePasswordServiceRequest Class](userchangepasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

