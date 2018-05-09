---
title: UserResetPasswordRequest.NewPassword Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NewPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest.NewPassword
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.userresetpasswordrequest.newpassword(v=AX.60)
ms:contentKeyID: 62213658
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest.NewPassword
dev_langs:
- CSharp
- C++
- VB
---

# NewPassword Property

Gets or sets the new password.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NewPassword As String
    Get
    Set
'Usage
Dim instance As UserResetPasswordRequest
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The new password.  

## See Also

#### Reference

[UserResetPasswordRequest Class](userresetpasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

