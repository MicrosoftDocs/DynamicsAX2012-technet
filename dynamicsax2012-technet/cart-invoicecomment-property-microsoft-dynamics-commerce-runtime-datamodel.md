---
title: Cart.InvoiceComment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InvoiceComment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.InvoiceComment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.invoicecomment(v=AX.60)
ms:contentKeyID: 65321766
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.InvoiceComment
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceComment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVOICECOMMENT")> _
<DataMemberAttribute> _
Public Property InvoiceComment As String
    Get
    Set
'Usage
Dim instance As Cart
Dim value As String

value = instance.InvoiceComment

instance.InvoiceComment = value
```

``` csharp
[ColumnAttribute("INVOICECOMMENT")]
[DataMemberAttribute]
public string InvoiceComment { get; set; }
```

``` c++
[ColumnAttribute(L"INVOICECOMMENT")]
[DataMemberAttribute]
public:
property String^ InvoiceComment {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

