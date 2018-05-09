---
title: SuspendCartResponse.Cart Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Cart Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SuspendCartResponse.Cart
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.suspendcartresponse.cart(v=AX.60)
ms:contentKeyID: 62213860
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SuspendCartResponse.Cart
dev_langs:
- CSharp
- C++
- VB
---

# Cart Property

Gets the suspended cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Cart As Cart
    Get
    Private Set
'Usage
Dim instance As SuspendCartResponse
Dim value As Cart

value = instance.Cart
```

``` csharp
public Cart Cart { get; private set; }
```

``` c++
public:
property Cart^ Cart {
    Cart^ get ();
    private: void set (Cart^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SuspendCartResponse Class](suspendcartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

