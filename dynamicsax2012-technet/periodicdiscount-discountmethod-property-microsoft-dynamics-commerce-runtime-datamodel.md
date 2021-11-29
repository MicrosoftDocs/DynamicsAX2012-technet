---
title: PeriodicDiscount.DiscountMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.discountmethod(v=AX.60)
ms:contentKeyID: 49832336
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountMethod
dev_langs:
- CSharp
- C++
- VB
---

# DiscountMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the method for how the discount offer will be applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTMETHOD")> _
<DataMemberAttribute> _
Public Property DiscountMethod As Integer
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Integer

value = instance.DiscountMethod
```

``` csharp
[ColumnAttribute("DISCOUNTMETHOD")]
[DataMemberAttribute]
public int DiscountMethod { get; internal set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTMETHOD")]
[DataMemberAttribute]
public:
property int DiscountMethod {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

