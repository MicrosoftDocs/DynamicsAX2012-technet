---
title: SalesLine.InvoiceAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InvoiceAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.InvoiceAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.invoiceamount(v=AX.60)
ms:contentKeyID: 62212757
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.InvoiceAmount
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating the invoice amount if this instance is an invoice line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVOICEAMOUNT")> _
Public Property InvoiceAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.InvoiceAmount

instance.InvoiceAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVOICEAMOUNT")]
public decimal InvoiceAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVOICEAMOUNT")]
public:
property Decimal InvoiceAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

