---
title: LoyaltySchemeLineEarn.FromActivityAmountQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromActivityAmountQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromActivityAmountQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.fromactivityamountquantity(v=AX.60)
ms:contentKeyID: 62209617
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromActivityAmountQuantity
dev_langs:
- CSharp
- C++
- VB
---

# FromActivityAmountQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the amount or the quantity of the activity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FROMACTIVITYAMOUNTQTY")> _
Public Property FromActivityAmountQuantity As Decimal
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As Decimal

value = instance.FromActivityAmountQuantity
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FROMACTIVITYAMOUNTQTY")]
public decimal FromActivityAmountQuantity { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FROMACTIVITYAMOUNTQTY")]
public:
property Decimal FromActivityAmountQuantity {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

