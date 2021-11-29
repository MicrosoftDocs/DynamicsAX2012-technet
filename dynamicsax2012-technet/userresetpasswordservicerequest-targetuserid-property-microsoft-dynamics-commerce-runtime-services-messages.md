---
title: UserResetPasswordServiceRequest.TargetUserId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TargetUserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest.TargetUserId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userresetpasswordservicerequest.targetuserid(v=AX.60)
ms:contentKeyID: 62208158
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest.TargetUserId
dev_langs:
- CSharp
- C++
- VB
---

# TargetUserId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the target user id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TargetUserId As String
    Get
    Set
'Usage
Dim instance As UserResetPasswordServiceRequest
Dim value As String

value = instance.TargetUserId

instance.TargetUserId = value
```

``` csharp
[DataMemberAttribute]
public string TargetUserId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TargetUserId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The target user id.  

## See Also

#### Reference

[UserResetPasswordServiceRequest Class](userresetpasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

