---
title: UserAuthenticationRequest.NeedChannelIdFromPrincipal Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NeedChannelIdFromPrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.NeedChannelIdFromPrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userauthenticationrequest.needchannelidfromprincipal(v=AX.60)
ms:contentKeyID: 62209243
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.NeedChannelIdFromPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# NeedChannelIdFromPrincipal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the channel should be retrieved from principal for the specific request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overrides ReadOnly Property NeedChannelIdFromPrincipal As Boolean
    Get
'Usage
Dim instance As UserAuthenticationRequest
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
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[UserAuthenticationRequest Class](userauthenticationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

