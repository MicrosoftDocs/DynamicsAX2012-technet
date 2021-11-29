---
title: IFiscalPrinterV2.SupportNormalPrinters Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SupportNormalPrinters Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.SupportNormalPrinters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv2.supportnormalprinters(v=AX.60)
ms:contentKeyID: 62204841
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.SupportNormalPrinters
dev_langs:
- CSharp
- C++
- VB
---

# SupportNormalPrinters Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Denotes whether the fiscal printer supports simultaneous printing on normal printers.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SupportNormalPrinters As Boolean
    Get
'Usage
Dim instance As IFiscalPrinterV2
Dim value As Boolean

value = instance.SupportNormalPrinters
```

``` csharp
bool SupportNormalPrinters { get; }
```

``` c++
property bool SupportNormalPrinters {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IFiscalPrinterV2 Interface](ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

