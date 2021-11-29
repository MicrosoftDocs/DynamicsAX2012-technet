---
title: ICorporateCardV1.VoidCardPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: VoidCardPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICorporateCardV1.VoidCardPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo,System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icorporatecardv1.voidcardpayment(v=AX.60)
ms:contentKeyID: 47344513
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICorporateCardV1.VoidCardPayment
dev_langs:
- CSharp
- C++
- VB
---

# VoidCardPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Voiding payment of a corporate card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub VoidCardPayment ( _
    cardInfo As ICardInfo, _
    posTransaction As Object _
)
'Usage
Dim instance As ICorporateCardV1
Dim cardInfo As ICardInfo
Dim posTransaction As Object

instance.VoidCardPayment(cardInfo, posTransaction)
```

``` csharp
void VoidCardPayment(
    ICardInfo cardInfo,
    Object posTransaction
)
```

``` c++
void VoidCardPayment(
    ICardInfo^ cardInfo, 
    Object^ posTransaction
)
```

#### Parameters

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

## See Also

#### Reference

[ICorporateCardV1 Interface](icorporatecardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

