---
title: CheckAccessServiceRequest.DeviceTokenRequired Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeviceTokenRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.DeviceTokenRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.checkaccessservicerequest.devicetokenrequired(v=AX.60)
ms:contentKeyID: 62206723
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.DeviceTokenRequired
dev_langs:
- CSharp
- C++
- VB
---

# DeviceTokenRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether device token is required.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceTokenRequired As Boolean
    Get
    Set
'Usage
Dim instance As CheckAccessServiceRequest
Dim value As Boolean

value = instance.DeviceTokenRequired

instance.DeviceTokenRequired = value
```

``` csharp
[DataMemberAttribute]
public bool DeviceTokenRequired { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool DeviceTokenRequired {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Device token required.  

## See Also

#### Reference

[CheckAccessServiceRequest Class](checkaccessservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

