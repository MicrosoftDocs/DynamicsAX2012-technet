---
title: IPrintingV1.PrintGiftCertificate Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintGiftCertificate Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintGiftCertificate(Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printgiftcertificate(v=AX.60)
ms:contentKeyID: 47343851
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintGiftCertificate
dev_langs:
- CSharp
- C++
- VB
---

# PrintGiftCertificate Method

Prints the gift card balance receipt.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintGiftCertificate ( _
    formType As FormType, _
    posTransaction As IPosTransaction, _
    giftCardLineItem As IGiftCardLineItem, _
    copyReceipt As Boolean _
)
'Usage
Dim instance As IPrintingV1
Dim formType As FormType
Dim posTransaction As IPosTransaction
Dim giftCardLineItem As IGiftCardLineItem
Dim copyReceipt As Boolean

instance.PrintGiftCertificate(formType, _
    posTransaction, giftCardLineItem, _
    copyReceipt)
```

``` csharp
void PrintGiftCertificate(
    FormType formType,
    IPosTransaction posTransaction,
    IGiftCardLineItem giftCardLineItem,
    bool copyReceipt
)
```

``` c++
void PrintGiftCertificate(
    FormType formType, 
    IPosTransaction^ posTransaction, 
    IGiftCardLineItem^ giftCardLineItem, 
    bool copyReceipt
)
```

#### Parameters

  - formType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType](formtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - giftCardLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem](igiftcardlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - copyReceipt  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IPrintingV1 Interface](iprintingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

