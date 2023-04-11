---
title: Cart.CartStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CartStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CartStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.cartstatus(v=AX.60)
ms:contentKeyID: 65317610
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CartStatus
dev_langs:
- CSharp
- C++
- VB
---

# CartStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property CartStatus As CartStatus
    Get
    Set
'Usage
Dim instance As Cart
Dim value As CartStatus

value = instance.CartStatus

instance.CartStatus = value
```

``` csharp
[IgnoreDataMemberAttribute]
public CartStatus CartStatus { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property CartStatus CartStatus {
    CartStatus get ();
    void set (CartStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartStatus](cartstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

