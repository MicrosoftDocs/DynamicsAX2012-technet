---
title: UserLogOnServiceRequest.Credential Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Credential Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.Credential
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonservicerequest.credential(v=AX.60)
ms:contentKeyID: 65321643
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.Credential
dev_langs:
- CSharp
- C++
- VB
---

# Credential Property

This member overrides [Request.Credential](request-credential-property-microsoft-dynamics-commerce-runtime-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overrides ReadOnly Property Credential As Credential
    Get
'Usage
Dim instance As UserLogOnServiceRequest
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

[UserLogOnServiceRequest Class](userlogonservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

