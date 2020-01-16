---
title: IFiscalPrinterV1.FiscalPrinterEnabled Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: FiscalPrinterEnabled Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.FiscalPrinterEnabled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.fiscalprinterenabled(v=AX.60)
ms:contentKeyID: 62202534
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.FiscalPrinterEnabled
dev_langs:
- CSharp
- C++
- VB
---

# FiscalPrinterEnabled Method

Verifies if the fiscal printer extension is enabled for the current store.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function FiscalPrinterEnabled As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim returnValue As Boolean

returnValue = instance.FiscalPrinterEnabled()
```

``` csharp
bool FiscalPrinterEnabled()
```

``` c++
bool FiscalPrinterEnabled()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns true if there is a fiscal printer implementation that must be called by the extension libraries; otherwise retuns FALSE.  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

