---
title: Cart.CustomerId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CustomerId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.customerid(v=AX.60)
ms:contentKeyID: 49851426
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CustomerId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerId Property

Gets or sets the customer identifier associated with this transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CUSTOMERID")> _
Public Property CustomerId As String
    Get
    Set
'Usage
Dim instance As Cart
Dim value As String

value = instance.CustomerId

instance.CustomerId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CUSTOMERID")]
public string CustomerId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CUSTOMERID")]
public:
property String^ CustomerId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Empty string if cart is not associated with customer. Null means value is not provided and original value will preserved.  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

