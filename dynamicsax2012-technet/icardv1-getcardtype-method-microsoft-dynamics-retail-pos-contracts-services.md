---
title: ICardV1.GetCardType Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetCardType Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV1.GetCardType(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icardv1.getcardtype(v=AX.60)
ms:contentKeyID: 47344435
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV1.GetCardType
dev_langs:
- CSharp
- C++
- VB
---

# GetCardType Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

In the current implementation, this method includes another method that first retrieves the data of all cards available.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetCardType ( _
    ByRef cardInfo As ICardInfo _
)
'Usage
Dim instance As ICardV1
Dim cardInfo As ICardInfo

instance.GetCardType(cardInfo)
```

``` csharp
void GetCardType(
    ref ICardInfo cardInfo
)
```

``` c++
void GetCardType(
    ICardInfo^% cardInfo
)
```

#### Parameters

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICardV1 Interface](icardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

