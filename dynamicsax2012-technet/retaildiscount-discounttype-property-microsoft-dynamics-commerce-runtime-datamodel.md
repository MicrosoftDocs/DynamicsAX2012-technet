---
title: RetailDiscount.DiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.DiscountType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.discounttype(v=AX.60)
ms:contentKeyID: 62206901
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.DiscountType
dev_langs:
- CSharp
- C++
- VB
---

# DiscountType Property

Gets or sets the discount type if this is a quantity discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTTYPE")> _
Public Property DiscountType As Integer
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Integer

value = instance.DiscountType

instance.DiscountType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTTYPE")]
public int DiscountType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTTYPE")]
public:
property int DiscountType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

