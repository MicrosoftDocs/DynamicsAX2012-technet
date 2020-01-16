---
title: RetailDiscount.PriceGroups Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.PriceGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.pricegroups(v=AX.60)
ms:contentKeyID: 62214502
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.PriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# PriceGroups Property

Gets or sets the retail discount price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PriceGroups As IList(Of RetailDiscountPriceGroup)
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As IList(Of RetailDiscountPriceGroup)

value = instance.PriceGroups

instance.PriceGroups = value
```

``` csharp
[DataMemberAttribute]
public IList<RetailDiscountPriceGroup> PriceGroups { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<RetailDiscountPriceGroup^>^ PriceGroups {
    IList<RetailDiscountPriceGroup^>^ get ();
    void set (IList<RetailDiscountPriceGroup^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[RetailDiscountPriceGroup](retaildiscountpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

