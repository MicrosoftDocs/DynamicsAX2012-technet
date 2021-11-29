---
title: DiscountLine.ManualDiscountTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ManualDiscountTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.ManualDiscountTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.manualdiscounttypevalue(v=AX.60)
ms:contentKeyID: 62204749
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.ManualDiscountTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# ManualDiscountTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the manual discount type enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ManualDiscountTypeValue As Integer
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Integer

value = instance.ManualDiscountTypeValue

instance.ManualDiscountTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int ManualDiscountTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ManualDiscountTypeValue {
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

