---
title: ChargeLine.FromAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.FromAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.fromamount(v=AX.60)
ms:contentKeyID: 62211580
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.FromAmount
dev_langs:
- CSharp
- C++
- VB
---

# FromAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets From Amount of the charge.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FromAmount As Decimal
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As Decimal

value = instance.FromAmount

instance.FromAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal FromAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal FromAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

From Amount for defining tiered charges.

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

