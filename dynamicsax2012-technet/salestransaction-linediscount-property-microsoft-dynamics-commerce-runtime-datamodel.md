---
title: SalesTransaction.LineDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LineDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.linediscount(v=AX.60)
ms:contentKeyID: 49849388
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LineDiscount
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total line discount given in this transaction minus the total discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CUSTDISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property LineDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.LineDiscount

instance.LineDiscount = value
```

``` csharp
[ColumnAttribute("CUSTDISCOUNTAMOUNT")]
[DataMemberAttribute]
public decimal LineDiscount { get; set; }
```

``` c++
[ColumnAttribute(L"CUSTDISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Decimal LineDiscount {
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

