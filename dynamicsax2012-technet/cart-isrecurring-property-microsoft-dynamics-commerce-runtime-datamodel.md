---
title: Cart.IsRecurring Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsRecurring Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.IsRecurring
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cart.isrecurring(v=AX.60)
ms:contentKeyID: 62213043
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.IsRecurring
dev_langs:
- CSharp
- C++
- VB
---

# IsRecurring Property

Gets or sets a value indicating whether wish list is recurring.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RECURRING")> _
Public Property IsRecurring As Boolean
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Boolean

value = instance.IsRecurring

instance.IsRecurring = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RECURRING")]
public bool IsRecurring { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RECURRING")]
public:
property bool IsRecurring {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

