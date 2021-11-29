---
title: RetailDiscountLine.DiscountMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.DiscountMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountline.discountmethod(v=AX.60)
ms:contentKeyID: 62210031
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.DiscountMethod
dev_langs:
- CSharp
- C++
- VB
---

# DiscountMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the method for how the discount offer will be applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTMETHOD")> _
Public Property DiscountMethod As Integer
    Get
    Set
'Usage
Dim instance As RetailDiscountLine
Dim value As Integer

value = instance.DiscountMethod

instance.DiscountMethod = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTMETHOD")]
public int DiscountMethod { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTMETHOD")]
public:
property int DiscountMethod {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscountLine Class](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

