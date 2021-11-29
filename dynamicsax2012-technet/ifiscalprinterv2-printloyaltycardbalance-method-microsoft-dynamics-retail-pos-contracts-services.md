---
title: IFiscalPrinterV2.PrintLoyaltyCardBalance Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintLoyaltyCardBalance Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.PrintLoyaltyCardBalance(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardData)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv2.printloyaltycardbalance(v=AX.60)
ms:contentKeyID: 62203121
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.PrintLoyaltyCardBalance
dev_langs:
- CSharp
- C++
- VB
---

# PrintLoyaltyCardBalance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prints the loyalty card balance.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintLoyaltyCardBalance ( _
    loyaltyCardData As ILoyaltyCardData _
)
'Usage
Dim instance As IFiscalPrinterV2
Dim loyaltyCardData As ILoyaltyCardData

instance.PrintLoyaltyCardBalance(loyaltyCardData)
```

``` csharp
void PrintLoyaltyCardBalance(
    ILoyaltyCardData loyaltyCardData
)
```

``` c++
void PrintLoyaltyCardBalance(
    ILoyaltyCardData^ loyaltyCardData
)
```

#### Parameters

  - loyaltyCardData  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardData](iloyaltycarddata-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IFiscalPrinterV2 Interface](ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

