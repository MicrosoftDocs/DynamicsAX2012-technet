---
title: UserAuthenticationRequest.DeviceId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DeviceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.DeviceId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userauthenticationrequest.deviceid(v=AX.60)
ms:contentKeyID: 62215159
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.DeviceId
dev_langs:
- CSharp
- C++
- VB
---

# DeviceId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the device identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceId As String
    Get
    Set
'Usage
Dim instance As UserAuthenticationRequest
Dim value As String

value = instance.DeviceId

instance.DeviceId = value
```

``` csharp
[DataMemberAttribute]
public string DeviceId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The device identifier.  

## See Also

#### Reference

[UserAuthenticationRequest Class](userauthenticationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

