---
title: UserLogOffRequest.DeviceToken Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DeviceToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest.DeviceToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userlogoffrequest.devicetoken(v=AX.60)
ms:contentKeyID: 62209485
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest.DeviceToken
dev_langs:
- CSharp
- C++
- VB
---

# DeviceToken Property

Gets or sets the device token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceToken As String
    Get
    Set
'Usage
Dim instance As UserLogOffRequest
Dim value As String

value = instance.DeviceToken

instance.DeviceToken = value
```

``` csharp
[DataMemberAttribute]
public string DeviceToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The device token.  

## See Also

#### Reference

[UserLogOffRequest Class](userlogoffrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

