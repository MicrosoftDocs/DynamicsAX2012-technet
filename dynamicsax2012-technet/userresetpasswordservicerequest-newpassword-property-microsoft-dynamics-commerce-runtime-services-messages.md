---
title: UserResetPasswordServiceRequest.NewPassword Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NewPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest.NewPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userresetpasswordservicerequest.newpassword(v=AX.60)
ms:contentKeyID: 62211225
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest.NewPassword
dev_langs:
- CSharp
- C++
- VB
---

# NewPassword Property

Gets or sets the new password.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NewPassword As String
    Get
    Set
'Usage
Dim instance As UserResetPasswordServiceRequest
Dim value As String

value = instance.NewPassword

instance.NewPassword = value
```

``` csharp
[DataMemberAttribute]
public string NewPassword { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ NewPassword {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The new password.  

## See Also

#### Reference

[UserResetPasswordServiceRequest Class](userresetpasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

