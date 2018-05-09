---
title: IPrintingV1.PrintTenderDeclaration Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintTenderDeclaration Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintTenderDeclaration(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printtenderdeclaration(v=AX.60)
ms:contentKeyID: 47344237
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintTenderDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# PrintTenderDeclaration Method

Prints the tender declaration receipt, triggered when a tender declaration transaction is made.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintTenderDeclaration ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IPrintingV1
Dim posTransaction As IPosTransaction

instance.PrintTenderDeclaration(posTransaction)
```

``` csharp
void PrintTenderDeclaration(
    IPosTransaction posTransaction
)
```

``` c++
void PrintTenderDeclaration(
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

