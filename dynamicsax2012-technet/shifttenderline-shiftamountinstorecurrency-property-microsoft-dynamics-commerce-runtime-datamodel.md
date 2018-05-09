---
title: ShiftTenderLine.ShiftAmountInStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShiftAmountInStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.ShiftAmountInStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.shiftamountinstorecurrency(v=AX.60)
ms:contentKeyID: 62213144
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.ShiftAmountInStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ShiftAmountInStoreCurrency Property

Gets expected shift amount of tender in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overridable ReadOnly Property ShiftAmountInStoreCurrency As Decimal
    Get
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.ShiftAmountInStoreCurrency
```

``` csharp
[IgnoreDataMemberAttribute]
public virtual decimal ShiftAmountInStoreCurrency { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property Decimal ShiftAmountInStoreCurrency {
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

