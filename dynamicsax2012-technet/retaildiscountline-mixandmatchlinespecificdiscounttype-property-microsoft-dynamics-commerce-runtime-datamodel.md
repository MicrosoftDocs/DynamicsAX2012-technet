---
title: RetailDiscountLine.MixAndMatchLineSpecificDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchLineSpecificDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.MixAndMatchLineSpecificDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountline.mixandmatchlinespecificdiscounttype(v=AX.60)
ms:contentKeyID: 62209472
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.MixAndMatchLineSpecificDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchLineSpecificDiscountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount method for this line if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MIXANDMATCHLINEDISCOUNTTYPE")> _
Public Property MixAndMatchLineSpecificDiscountType As Integer
    Get
    Set
'Usage
Dim instance As RetailDiscountLine
Dim value As Integer

value = instance.MixAndMatchLineSpecificDiscountType

instance.MixAndMatchLineSpecificDiscountType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MIXANDMATCHLINEDISCOUNTTYPE")]
public int MixAndMatchLineSpecificDiscountType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MIXANDMATCHLINEDISCOUNTTYPE")]
public:
property int MixAndMatchLineSpecificDiscountType {
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

