---
title: SalesTransaction.TotalDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TotalDiscount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.totaldiscount(v=AX.60)
ms:contentKeyID: 49841032
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TotalDiscount
dev_langs:
- CSharp
- C++
- VB
---

# TotalDiscount Property

Gets or sets the total discount given in this transaction excluding the line discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TOTALDISCOUNTAMOUNT")> _
Public Property TotalDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.TotalDiscount

instance.TotalDiscount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TOTALDISCOUNTAMOUNT")]
public decimal TotalDiscount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TOTALDISCOUNTAMOUNT")]
public:
property Decimal TotalDiscount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

