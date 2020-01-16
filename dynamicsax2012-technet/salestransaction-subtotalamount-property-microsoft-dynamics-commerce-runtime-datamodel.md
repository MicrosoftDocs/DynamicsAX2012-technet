---
title: SalesTransaction.SubtotalAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SubtotalAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.SubtotalAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.subtotalamount(v=AX.60)
ms:contentKeyID: 62209494
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.SubtotalAmount
dev_langs:
- CSharp
- C++
- VB
---

# SubtotalAmount Property

Gets or sets the subtotal amount on this sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SUBTOTALAMOUNT")> _
Public Property SubtotalAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.SubtotalAmount

instance.SubtotalAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SUBTOTALAMOUNT")]
public decimal SubtotalAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SUBTOTALAMOUNT")]
public:
property Decimal SubtotalAmount {
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

