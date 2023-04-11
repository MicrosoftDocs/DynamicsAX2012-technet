---
title: LoyaltyCard.LoyaltyGroups Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: LoyaltyGroups Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyCard.LoyaltyGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.loyaltycard.loyaltygroups(v=AX.60)
ms:contentKeyID: 65318105
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyCard.LoyaltyGroups
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyGroups Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyGroups As IList(Of LoyaltyGroup)
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As IList(Of LoyaltyGroup)

value = instance.LoyaltyGroups

instance.LoyaltyGroups = value
```

``` csharp
[DataMemberAttribute]
public IList<LoyaltyGroup> LoyaltyGroups { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<LoyaltyGroup^>^ LoyaltyGroups {
    IList<LoyaltyGroup^>^ get ();
    void set (IList<LoyaltyGroup^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyGroup](loyaltygroup-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

