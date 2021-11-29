---
title: SalesLine.IsInvoiceSettled Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsInvoiceSettled Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsInvoiceSettled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.isinvoicesettled(v=AX.60)
ms:contentKeyID: 62211920
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsInvoiceSettled
dev_langs:
- CSharp
- C++
- VB
---

# IsInvoiceSettled Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the invoice line has been settled if this instance is an invoice line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("ISINVOICESETTLEDCOLUMN")> _
<ColumnAttribute("ISINVOICESETTLEDCOLUMN")> _
Public Property IsInvoiceSettled As Boolean
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Boolean

value = instance.IsInvoiceSettled

instance.IsInvoiceSettled = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("ISINVOICESETTLEDCOLUMN")]
[ColumnAttribute("ISINVOICESETTLEDCOLUMN")]
public bool IsInvoiceSettled { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"ISINVOICESETTLEDCOLUMN")]
[ColumnAttribute(L"ISINVOICESETTLEDCOLUMN")]
public:
property bool IsInvoiceSettled {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

