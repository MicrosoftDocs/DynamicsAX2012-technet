---
title: UserChangePasswordRequest.OldPassword Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OldPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserChangePasswordRequest.OldPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userchangepasswordrequest.oldpassword(v=AX.60)
ms:contentKeyID: 62213827
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserChangePasswordRequest.OldPassword
dev_langs:
- CSharp
- C++
- VB
---

# OldPassword Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the staff password.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OldPassword As String
    Get
    Set
'Usage
Dim instance As UserChangePasswordRequest
Dim value As String

value = instance.OldPassword

instance.OldPassword = value
```

``` csharp
[DataMemberAttribute]
public string OldPassword { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OldPassword {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The staff old password.  

## See Also

#### Reference

[UserChangePasswordRequest Class](userchangepasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

