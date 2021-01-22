---
title: CartLineData.IsInvoiceLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsInvoiceLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsInvoiceLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.isinvoiceline(v=AX.60)
ms:contentKeyID: 62205697
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsInvoiceLine
dev_langs:
- CSharp
- C++
- VB
---

# IsInvoiceLine Property

Gets or sets a value indicating whether this instance is an invoice line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISINVOICELINE")> _
Public Property IsInvoiceLine As Boolean
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Boolean

value = instance.IsInvoiceLine

instance.IsInvoiceLine = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISINVOICELINE")]
public bool IsInvoiceLine { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISINVOICELINE")]
public:
property bool IsInvoiceLine {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

