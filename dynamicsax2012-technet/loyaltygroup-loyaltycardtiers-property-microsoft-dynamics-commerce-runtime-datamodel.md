---
title: LoyaltyGroup.LoyaltyCardTiers Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyCardTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyGroup.LoyaltyCardTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltygroup.loyaltycardtiers(v=AX.60)
ms:contentKeyID: 62204158
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyGroup.LoyaltyCardTiers
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTiers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty card tiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardTiers As IList(Of LoyaltyCardTier)
    Get
    Set
'Usage
Dim instance As LoyaltyGroup
Dim value As IList(Of LoyaltyCardTier)

value = instance.LoyaltyCardTiers

instance.LoyaltyCardTiers = value
```

``` csharp
[DataMemberAttribute]
public IList<LoyaltyCardTier> LoyaltyCardTiers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<LoyaltyCardTier^>^ LoyaltyCardTiers {
    IList<LoyaltyCardTier^>^ get ();
    void set (IList<LoyaltyCardTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyCardTier](loyaltycardtier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyGroup Class](loyaltygroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

