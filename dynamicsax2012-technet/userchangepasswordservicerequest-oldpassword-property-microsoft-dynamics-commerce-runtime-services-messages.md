---
title: UserChangePasswordServiceRequest.OldPassword Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: OldPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest.OldPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userchangepasswordservicerequest.oldpassword(v=AX.60)
ms:contentKeyID: 62212937
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest.OldPassword
dev_langs:
- CSharp
- C++
- VB
---

# OldPassword Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the old password.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OldPassword As String
    Get
    Set
'Usage
Dim instance As UserChangePasswordServiceRequest
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
The new password.  

## See Also

#### Reference

[UserChangePasswordServiceRequest Class](userchangepasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

