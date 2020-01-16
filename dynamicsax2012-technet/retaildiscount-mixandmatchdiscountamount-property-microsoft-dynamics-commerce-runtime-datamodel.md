---
title: RetailDiscount.MixAndMatchDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.mixandmatchdiscountamount(v=AX.60)
ms:contentKeyID: 62207431
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchDiscountAmount Property

Gets or sets the amount off of a mix and match set if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTAMOUNTVALUE")> _
Public Property MixAndMatchDiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Decimal

value = instance.MixAndMatchDiscountAmount

instance.MixAndMatchDiscountAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTAMOUNTVALUE")]
public decimal MixAndMatchDiscountAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTAMOUNTVALUE")]
public:
property Decimal MixAndMatchDiscountAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

