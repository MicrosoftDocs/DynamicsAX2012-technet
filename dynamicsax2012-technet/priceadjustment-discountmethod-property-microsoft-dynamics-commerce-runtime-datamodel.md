---
title: PriceAdjustment.DiscountMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.DiscountMethod
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.discountmethod(v=AX.60)
ms:contentKeyID: 49844038
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.DiscountMethod
dev_langs:
- CSharp
- C++
- VB
---

# DiscountMethod Property

Gets the method for how the price adjustment will be applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTMETHOD")> _
<DataMemberAttribute> _
Public Property DiscountMethod As DiscountOfferMethod
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As DiscountOfferMethod

value = instance.DiscountMethod
```

``` csharp
[ColumnAttribute("DISCOUNTMETHOD")]
[DataMemberAttribute]
public DiscountOfferMethod DiscountMethod { get; internal set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTMETHOD")]
[DataMemberAttribute]
public:
property DiscountOfferMethod DiscountMethod {
    DiscountOfferMethod get ();
    internal: void set (DiscountOfferMethod value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountOfferMethod](discountoffermethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DiscountOfferMethod](discountoffermethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

