---
title: LoyaltyGroup.LoyaltyTiers Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: LoyaltyTiers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyGroup.LoyaltyTiers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.loyaltygroup.loyaltytiers(v=AX.60)
ms:contentKeyID: 65315711
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyGroup.LoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTiers Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

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

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[LoyaltyTier](loyaltytier-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LoyaltyGroup Class](loyaltygroup-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

