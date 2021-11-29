---
title: SalesInvoice.Amount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Amount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.Amount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice.amount(v=AX.60)
ms:contentKeyID: 62208549
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.Amount
dev_langs:
- CSharp
- C++
- VB
---

# Amount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the invoice amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVOICEAMOUNT")> _
Public Property Amount As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoice
Dim value As Decimal

value = instance.Amount

instance.Amount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVOICEAMOUNT")]
public decimal Amount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVOICEAMOUNT")]
public:
property Decimal Amount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The invoice amount.  

## See Also

#### Reference

[SalesInvoice Class](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

