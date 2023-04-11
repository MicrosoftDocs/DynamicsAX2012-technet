---
title: IGiftCardV1.IssueGiftCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IssueGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.IssueGiftCard(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITender)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.igiftcardv1.issuegiftcard(v=AX.60)
ms:contentKeyID: 47344510
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.IssueGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# IssueGiftCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Issues a gift card and adds it to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub IssueGiftCard ( _
    posTransaction As IPosTransaction, _
    gcTenderInfo As ITender _
)
'Usage
Dim instance As IGiftCardV1
Dim posTransaction As IPosTransaction
Dim gcTenderInfo As ITender

instance.IssueGiftCard(posTransaction, _
    gcTenderInfo)
```

``` csharp
void IssueGiftCard(
    IPosTransaction posTransaction,
    ITender gcTenderInfo
)
```

``` c++
void IssueGiftCard(
    IPosTransaction^ posTransaction, 
    ITender^ gcTenderInfo
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - gcTenderInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITender](itender-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IGiftCardV1 Interface](igiftcardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

