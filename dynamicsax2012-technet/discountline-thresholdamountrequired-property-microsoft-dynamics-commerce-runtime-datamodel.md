---
title: DiscountLine.ThresholdAmountRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ThresholdAmountRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.ThresholdAmountRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.thresholdamountrequired(v=AX.60)
ms:contentKeyID: 62208989
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.ThresholdAmountRequired
dev_langs:
- CSharp
- C++
- VB
---

# ThresholdAmountRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total required to trigger this threshold discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ThresholdAmountRequired As Decimal
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Decimal

value = instance.ThresholdAmountRequired

instance.ThresholdAmountRequired = value
```

``` csharp
[DataMemberAttribute]
public decimal ThresholdAmountRequired { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ThresholdAmountRequired {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

