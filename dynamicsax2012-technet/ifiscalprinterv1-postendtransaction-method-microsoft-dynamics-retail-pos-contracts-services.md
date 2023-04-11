---
title: IFiscalPrinterV1.PostEndTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PostEndTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostEndTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.postendtransaction(v=AX.60)
ms:contentKeyID: 62202766
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostEndTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PostEndTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered at the end a transaction, after saving the transaction and printing of receipts

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostEndTransaction ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim posTransaction As IPosTransaction

instance.PostEndTransaction(posTransaction)
```

``` csharp
void PostEndTransaction(
    IPosTransaction posTransaction
)
```

``` c++
void PostEndTransaction(
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

