---
title: IFiscalPrinterV1.PostVoidPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PostVoidPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostVoidPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.postvoidpayment(v=AX.60)
ms:contentKeyID: 62203702
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostVoidPayment
dev_langs:
- CSharp
- C++
- VB
---

# PostVoidPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after voiding of a payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostVoidPayment ( _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PostVoidPayment(posTransaction, _
    lineId)
```

``` csharp
void PostVoidPayment(
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PostVoidPayment(
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

