---
title: IFiscalPrinterV2.SupportPrintingReceiptInNonFiscalMode Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SupportPrintingReceiptInNonFiscalMode Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.SupportPrintingReceiptInNonFiscalMode(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv2.supportprintingreceiptinnonfiscalmode(v=AX.60)
ms:contentKeyID: 62204286
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.SupportPrintingReceiptInNonFiscalMode
dev_langs:
- CSharp
- C++
- VB
---

# SupportPrintingReceiptInNonFiscalMode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Determines whether the fiscal printer supports printing receipt in non fiscal mode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function SupportPrintingReceiptInNonFiscalMode ( _
    copyReceipt As Boolean _
) As Boolean
'Usage
Dim instance As IFiscalPrinterV2
Dim copyReceipt As Boolean
Dim returnValue As Boolean

returnValue = instance.SupportPrintingReceiptInNonFiscalMode(copyReceipt)
```

``` csharp
bool SupportPrintingReceiptInNonFiscalMode(
    bool copyReceipt
)
```

``` c++
bool SupportPrintingReceiptInNonFiscalMode(
    bool copyReceipt
)
```

#### Parameters

  - copyReceipt  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the fiscal printer supports printing receipt in non fiscal mode; false otherwise.  

## See Also

#### Reference

[IFiscalPrinterV2 Interface](ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

