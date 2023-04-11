---
title: Cart.CustomerOrderModeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerOrderModeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CustomerOrderModeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.customerordermodevalue(v=AX.60)
ms:contentKeyID: 62213651
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CustomerOrderModeValue
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderModeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer order mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerOrderModeValue As Integer
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Integer

value = instance.CustomerOrderModeValue

instance.CustomerOrderModeValue = value
```

``` csharp
[DataMemberAttribute]
public int CustomerOrderModeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int CustomerOrderModeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

