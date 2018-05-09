---
title: ShiftTenderLine.OverShortAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OverShortAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.OverShortAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.overshortamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62210470
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.OverShortAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# OverShortAmountOfStoreCurrency Property

Gets difference between counted amount and excepted amount in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overridable ReadOnly Property OverShortAmountOfStoreCurrency As Decimal
    Get
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.OverShortAmountOfStoreCurrency
```

``` csharp
[IgnoreDataMemberAttribute]
public virtual decimal OverShortAmountOfStoreCurrency { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property Decimal OverShortAmountOfStoreCurrency {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

