---
title: CheckAccessRequest.DeviceTokenRequired Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DeviceTokenRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.DeviceTokenRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.checkaccessrequest.devicetokenrequired(v=AX.60)
ms:contentKeyID: 62209036
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.DeviceTokenRequired
dev_langs:
- CSharp
- C++
- VB
---

# DeviceTokenRequired Property

Gets a value indicating whether \[device token required\].

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceTokenRequired As Boolean
    Get
    Private Set
'Usage
Dim instance As CheckAccessRequest
Dim value As Boolean

value = instance.DeviceTokenRequired
```

``` csharp
[DataMemberAttribute]
public bool DeviceTokenRequired { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool DeviceTokenRequired {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if \[device token required\]; otherwise, false.  

## See Also

#### Reference

[CheckAccessRequest Class](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

