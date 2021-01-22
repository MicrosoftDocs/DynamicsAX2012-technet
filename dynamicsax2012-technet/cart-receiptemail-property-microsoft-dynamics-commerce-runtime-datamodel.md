---
title: Cart.ReceiptEmail Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptEmail Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.ReceiptEmail
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.receiptemail(v=AX.60)
ms:contentKeyID: 62212272
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.ReceiptEmail
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptEmail Property

Gets or sets the receipt email.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RECEIPTEMAIL")> _
<DataMemberAttribute> _
Public Property ReceiptEmail As String
    Get
    Set
'Usage
Dim instance As Cart
Dim value As String

value = instance.ReceiptEmail

instance.ReceiptEmail = value
```

``` csharp
[ColumnAttribute("RECEIPTEMAIL")]
[DataMemberAttribute]
public string ReceiptEmail { get; set; }
```

``` c++
[ColumnAttribute(L"RECEIPTEMAIL")]
[DataMemberAttribute]
public:
property String^ ReceiptEmail {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

