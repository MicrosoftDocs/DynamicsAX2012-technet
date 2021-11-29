---
title: UserChangePasswordRequest.NewPassword Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NewPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserChangePasswordRequest.NewPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userchangepasswordrequest.newpassword(v=AX.60)
ms:contentKeyID: 62205110
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserChangePasswordRequest.NewPassword
dev_langs:
- CSharp
- C++
- VB
---

# NewPassword Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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
Dim instance As UserChangePasswordRequest
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

[UserChangePasswordRequest Class](userchangepasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

