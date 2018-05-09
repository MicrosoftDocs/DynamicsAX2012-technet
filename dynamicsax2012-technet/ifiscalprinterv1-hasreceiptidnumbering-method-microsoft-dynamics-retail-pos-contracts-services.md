---
title: IFiscalPrinterV1.HasReceiptIdNumbering Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: HasReceiptIdNumbering Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.HasReceiptIdNumbering
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.hasreceiptidnumbering(v=AX.60)
ms:contentKeyID: 62204519
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.HasReceiptIdNumbering
dev_langs:
- CSharp
- C++
- VB
---

# HasReceiptIdNumbering Method

Determines whether the fiscal printer supports numbering function.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function HasReceiptIdNumbering As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim returnValue As Boolean

returnValue = instance.HasReceiptIdNumbering()
```

``` csharp
bool HasReceiptIdNumbering()
```

``` c++
bool HasReceiptIdNumbering()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns true if the numbering function is supported.  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

