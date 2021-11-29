---
title: IEFTV1.CapturePayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CapturePayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.CapturePayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieftv1.capturepayment(v=AX.60)
ms:contentKeyID: 47344492
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.CapturePayment
dev_langs:
- CSharp
- C++
- VB
---

# CapturePayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Captures the card payment by establishing a connection with the configured payment processor.

Once a connection to the broker is established, it attempts to capture the authorized card payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CapturePayment ( _
    eftInfo As IEFTInfo, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IEFTV1
Dim eftInfo As IEFTInfo
Dim posTransaction As IPosTransaction

instance.CapturePayment(eftInfo, posTransaction)
```

``` csharp
void CapturePayment(
    IEFTInfo eftInfo,
    IPosTransaction posTransaction
)
```

``` c++
void CapturePayment(
    IEFTInfo^ eftInfo, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - eftInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IEFTV1 Interface](ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

