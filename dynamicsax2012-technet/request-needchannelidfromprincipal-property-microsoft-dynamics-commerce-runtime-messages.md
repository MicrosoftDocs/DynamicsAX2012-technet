---
title: Request.NeedChannelIdFromPrincipal Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NeedChannelIdFromPrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.NeedChannelIdFromPrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.request.needchannelidfromprincipal(v=AX.60)
ms:contentKeyID: 62209890
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.NeedChannelIdFromPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# NeedChannelIdFromPrincipal Property

Gets a value indicating whether the channel should be retrieved from principal for the specific request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overridable ReadOnly Property NeedChannelIdFromPrincipal As Boolean
    Get
'Usage
Dim instance As Request
Dim value As Boolean

value = instance.NeedChannelIdFromPrincipal
```

``` csharp
[IgnoreDataMemberAttribute]
public virtual bool NeedChannelIdFromPrincipal { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property bool NeedChannelIdFromPrincipal {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

