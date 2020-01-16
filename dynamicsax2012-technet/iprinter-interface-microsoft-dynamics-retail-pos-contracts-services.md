---
title: IPrinter Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IPrinter Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprinter(v=AX.60)
ms:contentKeyID: 47344089
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinter
dev_langs:
- CSharp
- C++
- VB
---

# IPrinter Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinter interface for printer device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("6B686507-53B9-49C6-BD3F-32BE62CA02AA")> _
Public Interface IPrinter _
    Inherits IPrinterV1, IPeripheral, IPeripheralV1, IPeripheralV2,  _
    IPrinterV2
'Usage
Dim instance As IPrinter
```

``` csharp
[GuidAttribute("6B686507-53B9-49C6-BD3F-32BE62CA02AA")]
public interface IPrinter : IPrinterV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, IPrinterV2
```

``` c++
[GuidAttribute(L"6B686507-53B9-49C6-BD3F-32BE62CA02AA")]
public interface class IPrinter : IPrinterV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, IPrinterV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

