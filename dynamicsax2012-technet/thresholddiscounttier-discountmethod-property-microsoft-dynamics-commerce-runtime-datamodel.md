---
title: ThresholdDiscountTier.DiscountMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountTier.DiscountMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.thresholddiscounttier.discountmethod(v=AX.60)
ms:contentKeyID: 62211134
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountTier.DiscountMethod
dev_langs:
- CSharp
- C++
- VB
---

# DiscountMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of discount given by this tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTMETHOD")> _
Public Property DiscountMethod As ThresholdDiscountMethod
    Get
    Set
'Usage
Dim instance As ThresholdDiscountTier
Dim value As ThresholdDiscountMethod

value = instance.DiscountMethod

instance.DiscountMethod = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTMETHOD")]
public ThresholdDiscountMethod DiscountMethod { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTMETHOD")]
public:
property ThresholdDiscountMethod DiscountMethod {
    ThresholdDiscountMethod get ();
    void set (ThresholdDiscountMethod value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountMethod](thresholddiscountmethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ThresholdDiscountMethod](thresholddiscountmethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ThresholdDiscountTier Class](thresholddiscounttier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

