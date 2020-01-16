---
title: SalesTransaction.TaxAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TaxAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.taxamount(v=AX.60)
ms:contentKeyID: 49831984
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TaxAmount
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmount Property

Gets or sets the tax amount on this sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXAMOUNT")> _
<DataMemberAttribute> _
Public Property TaxAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.TaxAmount

instance.TaxAmount = value
```

``` csharp
[ColumnAttribute("TAXAMOUNT")]
[DataMemberAttribute]
public decimal TaxAmount { get; set; }
```

``` c++
[ColumnAttribute(L"TAXAMOUNT")]
[DataMemberAttribute]
public:
property Decimal TaxAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

