---
title: PeriodicDiscount.MixAndMatchLineSpecificDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchLineSpecificDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchLineSpecificDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.mixandmatchlinespecificdiscounttype(v=AX.60)
ms:contentKeyID: 49822655
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchLineSpecificDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchLineSpecificDiscountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the discount method for this line if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MIXANDMATCHLINEDISCOUNTTYPE")> _
<DataMemberAttribute> _
Public Property MixAndMatchLineSpecificDiscountType As Integer
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Integer

value = instance.MixAndMatchLineSpecificDiscountType
```

``` csharp
[ColumnAttribute("MIXANDMATCHLINEDISCOUNTTYPE")]
[DataMemberAttribute]
public int MixAndMatchLineSpecificDiscountType { get; internal set; }
```

``` c++
[ColumnAttribute(L"MIXANDMATCHLINEDISCOUNTTYPE")]
[DataMemberAttribute]
public:
property int MixAndMatchLineSpecificDiscountType {
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

