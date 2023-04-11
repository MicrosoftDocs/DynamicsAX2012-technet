---
title: ISalesOrderTransaction Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ISalesOrderTransaction Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesOrderTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalesordertransaction(v=AX.60)
ms:contentKeyID: 49843513
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesOrderTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ISalesOrderTransaction Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

ISalesOrderTransaction interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("09FF4C71-0E02-4804-80B1-32E77E2BBFA0")> _
Public Interface ISalesOrderTransaction _
    Inherits IRetailTransaction, IPosTransaction, IPosTransactionV1, IPosTransactionV2,  _
    IPosTransactionV3, IRetailTransactionV1, IRetailTransactionV2, IRetailTransactionV3, IRetailTransactionV4
'Usage
Dim instance As ISalesOrderTransaction
```

``` csharp
[GuidAttribute("09FF4C71-0E02-4804-80B1-32E77E2BBFA0")]
public interface ISalesOrderTransaction : IRetailTransaction, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3, IRetailTransactionV1, 
    IRetailTransactionV2, IRetailTransactionV3, IRetailTransactionV4
```

``` c++
[GuidAttribute(L"09FF4C71-0E02-4804-80B1-32E77E2BBFA0")]
public interface class ISalesOrderTransaction : IRetailTransaction, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3, IRetailTransactionV1, 
    IRetailTransactionV2, IRetailTransactionV3, IRetailTransactionV4
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

