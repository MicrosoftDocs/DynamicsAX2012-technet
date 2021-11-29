---
title: LoyaltyGroup.LoyaltyTiers Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyGroup.LoyaltyTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltygroup.loyaltytiers(v=AX.60)
ms:contentKeyID: 62214038
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyGroup.LoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTiers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty tiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyTiers As IList(Of LoyaltyTier)
    Get
    Set
'Usage
Dim instance As LoyaltyGroup
Dim value As IList(Of LoyaltyTier)

value = instance.LoyaltyTiers

instance.LoyaltyTiers = value
```

``` csharp
[DataMemberAttribute]
public IList<LoyaltyTier> LoyaltyTiers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<LoyaltyTier^>^ LoyaltyTiers {
    IList<LoyaltyTier^>^ get ();
    void set (IList<LoyaltyTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyTier](loyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyGroup Class](loyaltygroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

