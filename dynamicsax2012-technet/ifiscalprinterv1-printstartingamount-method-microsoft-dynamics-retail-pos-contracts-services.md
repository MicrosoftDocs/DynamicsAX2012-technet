---
title: IFiscalPrinterV1.PrintStartingAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintStartingAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintStartingAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.printstartingamount(v=AX.60)
ms:contentKeyID: 62203922
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintStartingAmount
dev_langs:
- CSharp
- C++
- VB
---

# PrintStartingAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Print Starting Amount Declaration Receipt

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintStartingAmount ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim posTransaction As IPosTransaction

instance.PrintStartingAmount(posTransaction)
```

``` csharp
void PrintStartingAmount(
    IPosTransaction posTransaction
)
```

``` c++
void PrintStartingAmount(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

