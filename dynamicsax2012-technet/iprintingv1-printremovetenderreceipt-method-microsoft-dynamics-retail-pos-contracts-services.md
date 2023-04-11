---
title: IPrintingV1.PrintRemoveTenderReceipt Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintRemoveTenderReceipt Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintRemoveTenderReceipt(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printremovetenderreceipt(v=AX.60)
ms:contentKeyID: 47344361
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintRemoveTenderReceipt
dev_langs:
- CSharp
- C++
- VB
---

# PrintRemoveTenderReceipt Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prints a tender-removal receipt, triggered when a Tender removal transaction is made.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintRemoveTenderReceipt ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IPrintingV1
Dim posTransaction As IPosTransaction

instance.PrintRemoveTenderReceipt(posTransaction)
```

``` csharp
void PrintRemoveTenderReceipt(
    IPosTransaction posTransaction
)
```

``` c++
void PrintRemoveTenderReceipt(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IPrintingV1 Interface](iprintingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

