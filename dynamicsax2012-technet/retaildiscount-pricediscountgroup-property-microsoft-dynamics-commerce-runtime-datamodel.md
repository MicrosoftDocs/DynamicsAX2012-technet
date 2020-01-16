---
title: RetailDiscount.PriceDiscountGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.PriceDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.pricediscountgroup(v=AX.60)
ms:contentKeyID: 62202597
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.PriceDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# PriceDiscountGroup Property

Gets or sets the price discount group this discount applies to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEDISCGROUP")> _
<DataMemberAttribute> _
Public Property PriceDiscountGroup As Long
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Long

value = instance.PriceDiscountGroup

instance.PriceDiscountGroup = value
```

``` csharp
[ColumnAttribute("PRICEDISCGROUP")]
[DataMemberAttribute]
public long PriceDiscountGroup { get; set; }
```

``` c++
[ColumnAttribute(L"PRICEDISCGROUP")]
[DataMemberAttribute]
public:
property long long PriceDiscountGroup {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

