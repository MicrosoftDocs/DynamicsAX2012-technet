---
title: SalesTransaction.LoyaltyManualDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyManualDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LoyaltyManualDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.loyaltymanualdiscountamount(v=AX.60)
ms:contentKeyID: 62210899
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LoyaltyManualDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyManualDiscountAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the manual loyalty amount off value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOYALTYMANUALDISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property LoyaltyManualDiscountAmount As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Nullable(Of Decimal)

value = instance.LoyaltyManualDiscountAmount

instance.LoyaltyManualDiscountAmount = value
```

``` csharp
[ColumnAttribute("LOYALTYMANUALDISCOUNTAMOUNT")]
[DataMemberAttribute]
public Nullable<decimal> LoyaltyManualDiscountAmount { get; set; }
```

``` c++
[ColumnAttribute(L"LOYALTYMANUALDISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Nullable<Decimal> LoyaltyManualDiscountAmount {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

