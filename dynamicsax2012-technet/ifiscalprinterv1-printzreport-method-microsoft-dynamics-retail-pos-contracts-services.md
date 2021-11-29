---
title: IFiscalPrinterV1.PrintZReport Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintZReport Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintZReport(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.printzreport(v=AX.60)
ms:contentKeyID: 62202051
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintZReport
dev_langs:
- CSharp
- C++
- VB
---

# PrintZReport Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Print recently closed batch report (Z-Report)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintZReport ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim transaction As IPosTransaction

instance.PrintZReport(transaction)
```

``` csharp
void PrintZReport(
    IPosTransaction transaction
)
```

``` c++
void PrintZReport(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

