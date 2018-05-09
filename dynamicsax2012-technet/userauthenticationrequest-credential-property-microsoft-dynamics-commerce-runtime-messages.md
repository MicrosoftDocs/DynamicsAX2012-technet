---
title: UserAuthenticationRequest.Credential Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Credential Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.Credential
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.userauthenticationrequest.credential(v=AX.60)
ms:contentKeyID: 65316506
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.Credential
dev_langs:
- CSharp
- C++
- VB
---

# Credential Property

This member overrides [Request.Credential](request-credential-property-microsoft-dynamics-commerce-runtime-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overrides ReadOnly Property Credential As Credential
    Get
'Usage
Dim instance As UserAuthenticationRequest
Dim value As Credential

value = instance.Credential
```

``` csharp
[IgnoreDataMemberAttribute]
public override Credential Credential { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property Credential^ Credential {
    Credential^ get () override;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Framework.Credential](credential-class-microsoft-dynamics-commerce-runtime-framework.md)  

## See Also

#### Reference

[UserAuthenticationRequest Class](userauthenticationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

