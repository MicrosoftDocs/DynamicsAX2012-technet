---
title: ITenderRestrictionV1.FindTenderRestriction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: FindTenderRestriction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITenderRestrictionV1.FindTenderRestriction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.itenderrestrictionv1.findtenderrestriction(v=AX.60)
ms:contentKeyID: 47344002
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITenderRestrictionV1.FindTenderRestriction
dev_langs:
- CSharp
- C++
- VB
---

# FindTenderRestriction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Finds any tender restriction for the items in the transaction and the given card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function FindTenderRestriction ( _
    retailTransaction As IRetailTransaction, _
    cardInfo As ICardInfo _
) As Decimal
'Usage
Dim instance As ITenderRestrictionV1
Dim retailTransaction As IRetailTransaction
Dim cardInfo As ICardInfo
Dim returnValue As Decimal

returnValue = instance.FindTenderRestriction(retailTransaction, _
    cardInfo)
```

``` csharp
decimal FindTenderRestriction(
    IRetailTransaction retailTransaction,
    ICardInfo cardInfo
)
```

``` c++
Decimal FindTenderRestriction(
    IRetailTransaction^ retailTransaction, 
    ICardInfo^ cardInfo
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The amount allowed to be paid with the corporate card.  

## See Also

#### Reference

[ITenderRestrictionV1 Interface](itenderrestrictionv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

