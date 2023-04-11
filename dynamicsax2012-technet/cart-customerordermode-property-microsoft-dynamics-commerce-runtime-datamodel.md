---
title: Cart.CustomerOrderMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerOrderMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CustomerOrderMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.customerordermode(v=AX.60)
ms:contentKeyID: 62202901
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CustomerOrderMode
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer order mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CUSTOMERORDERMODE")> _
Public Property CustomerOrderMode As CustomerOrderMode
    Get
    Set
'Usage
Dim instance As Cart
Dim value As CustomerOrderMode

value = instance.CustomerOrderMode

instance.CustomerOrderMode = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CUSTOMERORDERMODE")]
public CustomerOrderMode CustomerOrderMode { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CUSTOMERORDERMODE")]
public:
property CustomerOrderMode CustomerOrderMode {
    CustomerOrderMode get ();
    void set (CustomerOrderMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode](customerordermode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CustomerOrderMode](customerordermode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

