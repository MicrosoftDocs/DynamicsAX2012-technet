---
title: SalesInvoice.InvoiceDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InvoiceDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.InvoiceDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice.invoicedate(v=AX.60)
ms:contentKeyID: 62213586
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.InvoiceDate
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceDate Property

Gets or sets the invoice date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVOICEDATE")> _
Public Property InvoiceDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As SalesInvoice
Dim value As Nullable(Of DateTimeOffset)

value = instance.InvoiceDate

instance.InvoiceDate = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVOICEDATE")]
public Nullable<DateTimeOffset> InvoiceDate { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVOICEDATE")]
public:
property Nullable<DateTimeOffset> InvoiceDate {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  
The invoice date (UTC).  

## See Also

#### Reference

[SalesInvoice Class](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

