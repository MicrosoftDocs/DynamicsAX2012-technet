---
title: IFiscalPrinterV3.AddToGiftCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddToGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV3.AddToGiftCard(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITender)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv3.addtogiftcard(v=AX.60)
ms:contentKeyID: 62202773
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV3.AddToGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# AddToGiftCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Add to gift card given the current transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddToGiftCard ( _
    retailTransaction As IRetailTransaction, _
    gcTenderInfo As ITender _
)
'Usage
Dim instance As IFiscalPrinterV3
Dim retailTransaction As IRetailTransaction
Dim gcTenderInfo As ITender

instance.AddToGiftCard(retailTransaction, _
    gcTenderInfo)
```

``` csharp
void AddToGiftCard(
    IRetailTransaction retailTransaction,
    ITender gcTenderInfo
)
```

``` c++
void AddToGiftCard(
    IRetailTransaction^ retailTransaction, 
    ITender^ gcTenderInfo
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - gcTenderInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITender](itender-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IFiscalPrinterV3 Interface](ifiscalprinterv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

