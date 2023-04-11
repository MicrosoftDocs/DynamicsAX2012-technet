---
title: IPrintingV1.PrintBankDrop Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintBankDrop Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintBankDrop(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printbankdrop(v=AX.60)
ms:contentKeyID: 47344175
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintBankDrop
dev_langs:
- CSharp
- C++
- VB
---

# PrintBankDrop Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prints a bank drop receipt.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintBankDrop ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IPrintingV1
Dim posTransaction As IPosTransaction

instance.PrintBankDrop(posTransaction)
```

``` csharp
void PrintBankDrop(
    IPosTransaction posTransaction
)
```

``` c++
void PrintBankDrop(
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

