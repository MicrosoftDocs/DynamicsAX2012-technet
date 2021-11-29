---
title: Cart.IsSuspended Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSuspended Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.IsSuspended
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.issuspended(v=AX.60)
ms:contentKeyID: 62213495
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.IsSuspended
dev_langs:
- CSharp
- C++
- VB
---

# IsSuspended Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the transaction has been suspended.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("ISSUSPENDED")> _
<ColumnAttribute("ISSUSPENDED")> _
Public Property IsSuspended As Boolean
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Boolean

value = instance.IsSuspended

instance.IsSuspended = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("ISSUSPENDED")]
[ColumnAttribute("ISSUSPENDED")]
public bool IsSuspended { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"ISSUSPENDED")]
[ColumnAttribute(L"ISSUSPENDED")]
public:
property bool IsSuspended {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

