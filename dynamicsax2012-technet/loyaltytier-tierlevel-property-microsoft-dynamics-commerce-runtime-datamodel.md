---
title: LoyaltyTier.TierLevel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TierLevel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTier.TierLevel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltytier.tierlevel(v=AX.60)
ms:contentKeyID: 62213276
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTier.TierLevel
dev_langs:
- CSharp
- C++
- VB
---

# TierLevel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tier level. Bigger number means higher level.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TIERLEVEL")> _
<DataMemberAttribute> _
Public Property TierLevel As Decimal
    Get
    Friend Set
'Usage
Dim instance As LoyaltyTier
Dim value As Decimal

value = instance.TierLevel
```

``` csharp
[ColumnAttribute("TIERLEVEL")]
[DataMemberAttribute]
public decimal TierLevel { get; internal set; }
```

``` c++
[ColumnAttribute(L"TIERLEVEL")]
[DataMemberAttribute]
public:
property Decimal TierLevel {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyTier Class](loyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

