---
title: RetailDiscount.ShouldCountNonDiscountItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShouldCountNonDiscountItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ShouldCountNonDiscountItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.shouldcountnondiscountitems(v=AX.60)
ms:contentKeyID: 62211557
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ShouldCountNonDiscountItems
dev_langs:
- CSharp
- C++
- VB
---

# ShouldCountNonDiscountItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the threshold offer setting indicated whether non-discount items contribute to threshold amount trigger.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COUNTNONDISCOUNTITEMS")> _
Public Property ShouldCountNonDiscountItems As Integer
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Integer

value = instance.ShouldCountNonDiscountItems

instance.ShouldCountNonDiscountItems = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COUNTNONDISCOUNTITEMS")]
public int ShouldCountNonDiscountItems { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COUNTNONDISCOUNTITEMS")]
public:
property int ShouldCountNonDiscountItems {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

