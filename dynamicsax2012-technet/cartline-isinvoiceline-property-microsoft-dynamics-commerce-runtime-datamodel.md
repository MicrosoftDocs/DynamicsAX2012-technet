---
title: CartLine.IsInvoiceLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsInvoiceLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.IsInvoiceLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.isinvoiceline(v=AX.60)
ms:contentKeyID: 62207837
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.IsInvoiceLine
dev_langs:
- CSharp
- C++
- VB
---

# IsInvoiceLine Property

Gets or sets a value indicating whether the cart line is an invoice line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsInvoiceLine As Boolean
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Boolean

value = instance.IsInvoiceLine

instance.IsInvoiceLine = value
```

``` csharp
[DataMemberAttribute]
public bool IsInvoiceLine { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsInvoiceLine {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if this instance is an invoice line; otherwise, false.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

