---
title: ShiftTenderLine.OverShortAmountOfTenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OverShortAmountOfTenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.OverShortAmountOfTenderCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.overshortamountoftendercurrency(v=AX.60)
ms:contentKeyID: 62214438
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.OverShortAmountOfTenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# OverShortAmountOfTenderCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets difference between counted amount and excepted amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overridable ReadOnly Property OverShortAmountOfTenderCurrency As Decimal
    Get
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.OverShortAmountOfTenderCurrency
```

``` csharp
[IgnoreDataMemberAttribute]
public virtual decimal OverShortAmountOfTenderCurrency { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property Decimal OverShortAmountOfTenderCurrency {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

