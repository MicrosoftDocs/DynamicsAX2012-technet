---
title: KitTransactionLine.Quantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Quantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransactionLine.Quantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kittransactionline.quantity(v=AX.60)
ms:contentKeyID: 62211875
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransactionLine.Quantity
dev_langs:
- CSharp
- C++
- VB
---

# Quantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QTY")> _
<DataMemberAttribute> _
Public Property Quantity As Decimal
    Get
    Set
'Usage
Dim instance As KitTransactionLine
Dim value As Decimal

value = instance.Quantity

instance.Quantity = value
```

``` csharp
[ColumnAttribute("QTY")]
[DataMemberAttribute]
public decimal Quantity { get; set; }
```

``` c++
[ColumnAttribute(L"QTY")]
[DataMemberAttribute]
public:
property Decimal Quantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[KitTransactionLine Class](kittransactionline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

