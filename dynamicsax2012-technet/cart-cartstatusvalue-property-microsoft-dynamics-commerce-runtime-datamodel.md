---
title: Cart.CartStatusValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CartStatusValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CartStatusValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.cartstatusvalue(v=AX.60)
ms:contentKeyID: 65319459
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CartStatusValue
dev_langs:
- CSharp
- C++
- VB
---

# CartStatusValue Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartStatusValue As Integer
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Integer

value = instance.CartStatusValue

instance.CartStatusValue = value
```

``` csharp
[DataMemberAttribute]
public int CartStatusValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int CartStatusValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

