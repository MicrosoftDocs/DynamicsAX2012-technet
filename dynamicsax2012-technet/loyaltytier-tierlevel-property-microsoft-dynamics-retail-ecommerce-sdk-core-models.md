---
title: LoyaltyTier.TierLevel Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: TierLevel Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyTier.TierLevel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.loyaltytier.tierlevel(v=AX.60)
ms:contentKeyID: 65318790
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyTier.TierLevel
dev_langs:
- CSharp
- C++
- VB
---

# TierLevel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TierLevel As Decimal
    Get
    Set
'Usage
Dim instance As LoyaltyTier
Dim value As Decimal

value = instance.TierLevel

instance.TierLevel = value
```

``` csharp
[DataMemberAttribute]
public decimal TierLevel { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal TierLevel {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[LoyaltyTier Class](loyaltytier-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

