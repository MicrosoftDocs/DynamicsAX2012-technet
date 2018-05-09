---
title: RetailDiscount.ThresholdDiscountTiers Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ThresholdDiscountTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ThresholdDiscountTiers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.thresholddiscounttiers(v=AX.60)
ms:contentKeyID: 62207735
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ThresholdDiscountTiers
dev_langs:
- CSharp
- C++
- VB
---

# ThresholdDiscountTiers Property

Gets or sets the threshold discount tiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ThresholdDiscountTiers As IList(Of ThresholdDiscountTier)
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As IList(Of ThresholdDiscountTier)

value = instance.ThresholdDiscountTiers

instance.ThresholdDiscountTiers = value
```

``` csharp
[DataMemberAttribute]
public IList<ThresholdDiscountTier> ThresholdDiscountTiers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<ThresholdDiscountTier^>^ ThresholdDiscountTiers {
    IList<ThresholdDiscountTier^>^ get ();
    void set (IList<ThresholdDiscountTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[ThresholdDiscountTier](thresholddiscounttier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

