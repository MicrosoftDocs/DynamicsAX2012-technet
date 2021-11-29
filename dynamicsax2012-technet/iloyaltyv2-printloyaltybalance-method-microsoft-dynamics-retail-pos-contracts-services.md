---
title: ILoyaltyV2.PrintLoyaltyBalance Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintLoyaltyBalance Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV2.PrintLoyaltyBalance(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardData)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv2.printloyaltybalance(v=AX.60)
ms:contentKeyID: 62202978
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV2.PrintLoyaltyBalance
dev_langs:
- CSharp
- C++
- VB
---

# PrintLoyaltyBalance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Submits the request to print loyalty card balance to the printer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintLoyaltyBalance ( _
    loyaltyCardData As ILoyaltyCardData _
)
'Usage
Dim instance As ILoyaltyV2
Dim loyaltyCardData As ILoyaltyCardData

instance.PrintLoyaltyBalance(loyaltyCardData)
```

``` csharp
void PrintLoyaltyBalance(
    ILoyaltyCardData loyaltyCardData
)
```

``` c++
void PrintLoyaltyBalance(
    ILoyaltyCardData^ loyaltyCardData
)
```

#### Parameters

  - loyaltyCardData  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardData](iloyaltycarddata-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ILoyaltyV2 Interface](iloyaltyv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

