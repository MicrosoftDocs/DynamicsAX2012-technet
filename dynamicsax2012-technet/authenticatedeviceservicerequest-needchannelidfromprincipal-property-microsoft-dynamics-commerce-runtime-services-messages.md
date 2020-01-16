---
title: AuthenticateDeviceServiceRequest.NeedChannelIdFromPrincipal Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NeedChannelIdFromPrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest.NeedChannelIdFromPrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authenticatedeviceservicerequest.needchannelidfromprincipal(v=AX.60)
ms:contentKeyID: 65318504
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest.NeedChannelIdFromPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# NeedChannelIdFromPrincipal Property

This member overrides [Request.NeedChannelIdFromPrincipal](request-needchannelidfromprincipal-property-microsoft-dynamics-commerce-runtime-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overrides ReadOnly Property NeedChannelIdFromPrincipal As Boolean
    Get
'Usage
Dim instance As AuthenticateDeviceServiceRequest
Dim value As Boolean

value = instance.NeedChannelIdFromPrincipal
```

``` csharp
[IgnoreDataMemberAttribute]
public override bool NeedChannelIdFromPrincipal { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property bool NeedChannelIdFromPrincipal {
    bool get () override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AuthenticateDeviceServiceRequest Class](authenticatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

