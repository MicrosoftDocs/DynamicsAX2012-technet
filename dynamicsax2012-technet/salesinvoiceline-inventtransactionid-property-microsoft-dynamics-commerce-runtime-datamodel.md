---
title: SalesInvoiceLine.InventTransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventTransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.InventTransactionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.inventtransactionid(v=AX.60)
ms:contentKeyID: 62204326
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.InventTransactionId
dev_langs:
- CSharp
- C++
- VB
---

# InventTransactionId Property

Gets or sets the invent transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTTRANSID")> _
<DataMemberAttribute> _
Public Property InventTransactionId As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.InventTransactionId

instance.InventTransactionId = value
```

``` csharp
[ColumnAttribute("INVENTTRANSID")]
[DataMemberAttribute]
public string InventTransactionId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTTRANSID")]
[DataMemberAttribute]
public:
property String^ InventTransactionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The invent transaction identifier.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

