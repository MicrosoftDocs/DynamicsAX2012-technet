---
title: SuspendCartRequest.CartId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SuspendCartRequest.CartId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.suspendcartrequest.cartid(v=AX.60)
ms:contentKeyID: 62207805
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SuspendCartRequest.CartId
dev_langs:
- CSharp
- C++
- VB
---

# CartId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the cart identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property CartId As String
    Get
    Private Set
'Usage
Dim instance As SuspendCartRequest
Dim value As String

value = instance.CartId
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string CartId { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ CartId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SuspendCartRequest Class](suspendcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

