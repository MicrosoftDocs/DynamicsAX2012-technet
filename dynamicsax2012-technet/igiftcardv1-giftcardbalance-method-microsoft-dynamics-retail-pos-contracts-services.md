---
title: IGiftCardV1.GiftCardBalance Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GiftCardBalance Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.GiftCardBalance(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.igiftcardv1.giftcardbalance(v=AX.60)
ms:contentKeyID: 47343966
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.GiftCardBalance
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardBalance Method

Displays the balance amount of a gift card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GiftCardBalance ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IGiftCardV1
Dim posTransaction As IPosTransaction

instance.GiftCardBalance(posTransaction)
```

``` csharp
void GiftCardBalance(
    IPosTransaction posTransaction
)
```

``` c++
void GiftCardBalance(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IGiftCardV1 Interface](igiftcardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

