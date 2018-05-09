---
title: RetailDiscount.MultibuyQuantityTiers Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MultibuyQuantityTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MultibuyQuantityTiers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.multibuyquantitytiers(v=AX.60)
ms:contentKeyID: 62207098
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MultibuyQuantityTiers
dev_langs:
- CSharp
- C++
- VB
---

# MultibuyQuantityTiers Property

Gets or sets the multiple buy quantity tiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property MultibuyQuantityTiers As IList(Of QuantityDiscountLevel)
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As IList(Of QuantityDiscountLevel)

value = instance.MultibuyQuantityTiers

instance.MultibuyQuantityTiers = value
```

``` csharp
[DataMemberAttribute]
public IList<QuantityDiscountLevel> MultibuyQuantityTiers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<QuantityDiscountLevel^>^ MultibuyQuantityTiers {
    IList<QuantityDiscountLevel^>^ get ();
    void set (IList<QuantityDiscountLevel^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

