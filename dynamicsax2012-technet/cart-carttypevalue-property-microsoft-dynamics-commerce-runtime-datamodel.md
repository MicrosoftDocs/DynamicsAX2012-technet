---
title: Cart.CartTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CartTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CartTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cart.carttypevalue(v=AX.60)
ms:contentKeyID: 62209451
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CartTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# CartTypeValue Property

Gets or sets the value of the CartType. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartTypeValue As Integer
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Integer

value = instance.CartTypeValue

instance.CartTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int CartTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int CartTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

