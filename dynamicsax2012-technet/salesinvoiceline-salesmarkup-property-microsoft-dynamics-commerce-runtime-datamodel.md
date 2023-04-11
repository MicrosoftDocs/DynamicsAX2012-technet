---
title: SalesInvoiceLine.SalesMarkup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesMarkup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SalesMarkup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.salesmarkup(v=AX.60)
ms:contentKeyID: 62203953
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SalesMarkup
dev_langs:
- CSharp
- C++
- VB
---

# SalesMarkup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales markup.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESMARKUP")> _
<DataMemberAttribute> _
Public Property SalesMarkup As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As Decimal

value = instance.SalesMarkup

instance.SalesMarkup = value
```

``` csharp
[ColumnAttribute("SALESMARKUP")]
[DataMemberAttribute]
public decimal SalesMarkup { get; set; }
```

``` c++
[ColumnAttribute(L"SALESMARKUP")]
[DataMemberAttribute]
public:
property Decimal SalesMarkup {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The sales markup.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

