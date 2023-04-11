---
title: IPeripheralsV3.FiscalPrinter Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: FiscalPrinter Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV3.FiscalPrinter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv3.fiscalprinter(v=AX.60)
ms:contentKeyID: 62205595
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV3.FiscalPrinter
dev_langs:
- CSharp
- C++
- VB
---

# FiscalPrinter Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fiscal printer peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property FiscalPrinter As IFiscalPrinter
    Get
'Usage
Dim instance As IPeripheralsV3
Dim value As IFiscalPrinter

value = instance.FiscalPrinter
```

``` csharp
IFiscalPrinter FiscalPrinter { get; }
```

``` c++
property IFiscalPrinter^ FiscalPrinter {
    IFiscalPrinter^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinter](ifiscalprinter-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [IFiscalPrinter](ifiscalprinter-interface-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IPeripheralsV3 Interface](iperipheralsv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

