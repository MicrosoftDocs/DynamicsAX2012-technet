---
title: UserResetPasswordRequest.TargetUserId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TargetUserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest.TargetUserId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userresetpasswordrequest.targetuserid(v=AX.60)
ms:contentKeyID: 62214849
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest.TargetUserId
dev_langs:
- CSharp
- C++
- VB
---

# TargetUserId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the target user ID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TargetUserId As String
    Get
    Set
'Usage
Dim instance As UserResetPasswordRequest
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
The target user ID.  

## See Also

#### Reference

[UserResetPasswordRequest Class](userresetpasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

