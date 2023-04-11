---
title: Cart.CartLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CartLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CartLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.cartlines(v=AX.60)
ms:contentKeyID: 49851747
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CartLines
dev_langs:
- CSharp
- C++
- VB
---

# CartLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cart lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartLines As IList(Of CartLine)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As IList(Of CartLine)

value = instance.CartLines

instance.CartLines = value
```

``` csharp
[DataMemberAttribute]
public IList<CartLine> CartLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<CartLine^>^ CartLines {
    IList<CartLine^>^ get ();
    void set (IList<CartLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

