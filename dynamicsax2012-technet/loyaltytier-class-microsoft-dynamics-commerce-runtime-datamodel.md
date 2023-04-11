---
title: LoyaltyTier Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyTier Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltytier(v=AX.60)
ms:contentKeyID: 62213949
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTier
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTier Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Presents a loyalty tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class LoyaltyTier _
    Inherits CommerceEntity
'Usage
Dim instance As LoyaltyTier
```

``` csharp
[DataContractAttribute]
public class LoyaltyTier : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class LoyaltyTier : public CommerceEntity
```

## Remarks

A loyalty tier belongs to one loyalty group. One loyalty group can have zero or more loyalty tiers (e.g. Silver Tier, Gold Tier).

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTier  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

