---
title: IPrintingV1.PrintPackSlip Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintPackSlip Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintPackSlip(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printpackslip(v=AX.60)
ms:contentKeyID: 47344404
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintPackSlip
dev_langs:
- CSharp
- C++
- VB
---

# PrintPackSlip Method

Prints pack slip.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintPackSlip ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IPrintingV1
Dim posTransaction As IPosTransaction

instance.PrintPackSlip(posTransaction)
```

``` csharp
void PrintPackSlip(
    IPosTransaction posTransaction
)
```

``` c++
void PrintPackSlip(
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

