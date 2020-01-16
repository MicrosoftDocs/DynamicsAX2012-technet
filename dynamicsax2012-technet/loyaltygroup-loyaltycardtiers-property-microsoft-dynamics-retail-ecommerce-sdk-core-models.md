---
title: LoyaltyGroup.LoyaltyCardTiers Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: LoyaltyCardTiers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyGroup.LoyaltyCardTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.loyaltygroup.loyaltycardtiers(v=AX.60)
ms:contentKeyID: 65317605
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyGroup.LoyaltyCardTiers
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTiers Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

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

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyCardTier](loyaltycardtier-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LoyaltyGroup Class](loyaltygroup-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

