---
title: Cart.TransactionTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TransactionTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.transactiontypevalue(v=AX.60)
ms:contentKeyID: 65320041
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TransactionTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# TransactionTypeValue Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionTypeValue As Integer
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Integer

value = instance.TransactionTypeValue

instance.TransactionTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int TransactionTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int TransactionTypeValue {
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

