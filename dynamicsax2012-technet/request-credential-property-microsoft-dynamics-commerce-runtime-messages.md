---
title: Request.Credential Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Credential Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.Credential
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.request.credential(v=AX.60)
ms:contentKeyID: 65319568
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.Credential
dev_langs:
- CSharp
- C++
- VB
---

# Credential Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overridable ReadOnly Property Credential As Credential
    Get
'Usage
Dim instance As Request
Dim value As Credential

value = instance.Credential
```

``` csharp
[IgnoreDataMemberAttribute]
public virtual Credential Credential { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property Credential^ Credential {
    Credential^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Framework.Credential](credential-class-microsoft-dynamics-commerce-runtime-framework.md)  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

