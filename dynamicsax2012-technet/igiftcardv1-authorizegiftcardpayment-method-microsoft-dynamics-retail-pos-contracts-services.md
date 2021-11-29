---
title: IGiftCardV1.AuthorizeGiftCardPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeGiftCardPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.AuthorizeGiftCardPayment(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITender)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.igiftcardv1.authorizegiftcardpayment(v=AX.60)
ms:contentKeyID: 47344135
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.AuthorizeGiftCardPayment
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeGiftCardPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Validates a gift card being used as a payment and reserves the amount at the head office.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AuthorizeGiftCardPayment ( _
    ByRef valid As Boolean, _
    ByRef comment As String, _
    posTransaction As IPosTransaction, _
    cardInfo As ICardInfo, _
    gcTenderInfo As ITender _
)
'Usage
Dim instance As IGiftCardV1
Dim valid As Boolean
Dim comment As String
Dim posTransaction As IPosTransaction
Dim cardInfo As ICardInfo
Dim gcTenderInfo As ITender

instance.AuthorizeGiftCardPayment(valid, _
    comment, posTransaction, cardInfo, _
    gcTenderInfo)
```

``` csharp
void AuthorizeGiftCardPayment(
    ref bool valid,
    ref string comment,
    IPosTransaction posTransaction,
    ICardInfo cardInfo,
    ITender gcTenderInfo
)
```

``` c++
void AuthorizeGiftCardPayment(
    bool% valid, 
    String^% comment, 
    IPosTransaction^ posTransaction, 
    ICardInfo^ cardInfo, 
    ITender^ gcTenderInfo
)
```

#### Parameters

  - valid  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - gcTenderInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITender](itender-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IGiftCardV1 Interface](igiftcardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

