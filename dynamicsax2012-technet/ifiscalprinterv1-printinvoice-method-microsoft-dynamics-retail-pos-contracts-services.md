---
title: IFiscalPrinterV1.PrintInvoice Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintInvoice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintInvoice(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.printinvoice(v=AX.60)
ms:contentKeyID: 62205438
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintInvoice
dev_langs:
- CSharp
- C++
- VB
---

# PrintInvoice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Print invoice receipt.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintInvoice ( _
    posTransaction As IPosTransaction, _
    copyInvoice As Boolean, _
    printPreview As Boolean _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim posTransaction As IPosTransaction
Dim copyInvoice As Boolean
Dim printPreview As Boolean

instance.PrintInvoice(posTransaction, _
    copyInvoice, printPreview)
```

``` csharp
void PrintInvoice(
    IPosTransaction posTransaction,
    bool copyInvoice,
    bool printPreview
)
```

``` c++
void PrintInvoice(
    IPosTransaction^ posTransaction, 
    bool copyInvoice, 
    bool printPreview
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - copyInvoice  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - printPreview  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

