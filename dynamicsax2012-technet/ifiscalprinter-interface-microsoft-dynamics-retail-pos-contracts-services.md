---
title: IFiscalPrinter Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IFiscalPrinter Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinter(v=AX.60)
ms:contentKeyID: 62204514
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinter
dev_langs:
- CSharp
- C++
- VB
---

# IFiscalPrinter Interface

Interface for Fiscal printer device

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("250B941F-5527-420E-A87B-D8169265312D")> _
Public Interface IFiscalPrinter _
    Inherits IFiscalPrinterV1, IPeripheral, IPeripheralV1, IPeripheralV2,  _
    IFiscalPrinterV2, IFiscalPrinterV3
'Usage
Dim instance As IFiscalPrinter
```

``` csharp
[GuidAttribute("250B941F-5527-420E-A87B-D8169265312D")]
public interface IFiscalPrinter : IFiscalPrinterV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, IFiscalPrinterV2, IFiscalPrinterV3
```

``` c++
[GuidAttribute(L"250B941F-5527-420E-A87B-D8169265312D")]
public interface class IFiscalPrinter : IFiscalPrinterV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, IFiscalPrinterV2, IFiscalPrinterV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

