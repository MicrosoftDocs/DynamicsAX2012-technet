---
title: IFiscalPrinterV1.IsThirdPartyCardPaymentEnabled Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IsThirdPartyCardPaymentEnabled Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.IsThirdPartyCardPaymentEnabled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.isthirdpartycardpaymentenabled(v=AX.60)
ms:contentKeyID: 62205175
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.IsThirdPartyCardPaymentEnabled
dev_langs:
- CSharp
- C++
- VB
---

# IsThirdPartyCardPaymentEnabled Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Verifies if there is EFT service integrated

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsThirdPartyCardPaymentEnabled As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim returnValue As Boolean

returnValue = instance.IsThirdPartyCardPaymentEnabled()
```

``` csharp
bool IsThirdPartyCardPaymentEnabled()
```

``` c++
bool IsThirdPartyCardPaymentEnabled()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

