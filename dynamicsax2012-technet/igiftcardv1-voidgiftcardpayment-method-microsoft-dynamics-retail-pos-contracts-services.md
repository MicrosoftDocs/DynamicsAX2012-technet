---
title: IGiftCardV1.VoidGiftCardPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: VoidGiftCardPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.VoidGiftCardPayment(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.igiftcardv1.voidgiftcardpayment(v=AX.60)
ms:contentKeyID: 47343814
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.VoidGiftCardPayment
dev_langs:
- CSharp
- C++
- VB
---

# VoidGiftCardPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Voids the gift card payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub VoidGiftCardPayment ( _
    ByRef voided As Boolean, _
    ByRef comment As String, _
    gcTenderLineItem As IGiftCardTenderLineItem _
)
'Usage
Dim instance As IGiftCardV1
Dim voided As Boolean
Dim comment As String
Dim gcTenderLineItem As IGiftCardTenderLineItem

instance.VoidGiftCardPayment(voided, _
    comment, gcTenderLineItem)
```

``` csharp
void VoidGiftCardPayment(
    ref bool voided,
    ref string comment,
    IGiftCardTenderLineItem gcTenderLineItem
)
```

``` c++
void VoidGiftCardPayment(
    bool% voided, 
    String^% comment, 
    IGiftCardTenderLineItem^ gcTenderLineItem
)
```

#### Parameters

  - voided  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - gcTenderLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItem](igiftcardtenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IGiftCardV1 Interface](igiftcardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

