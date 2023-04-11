---
title: DiscountLine.PeriodicDiscountTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PeriodicDiscountTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.PeriodicDiscountTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.periodicdiscounttypevalue(v=AX.60)
ms:contentKeyID: 62212252
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.PeriodicDiscountTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the PeriodicDiscountOfferType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PeriodicDiscountTypeValue As Integer
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Integer

value = instance.PeriodicDiscountTypeValue

instance.PeriodicDiscountTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int PeriodicDiscountTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int PeriodicDiscountTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

