---
title: IFloatEntryTransaction Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IFloatEntryTransaction Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IFloatEntryTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ifloatentrytransaction(v=AX.60)
ms:contentKeyID: 49843098
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IFloatEntryTransaction
dev_langs:
- CSharp
- C++
- VB
---

# IFloatEntryTransaction Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

IFloatEntryTransaction interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("E87104E0-6CA0-41E2-AFF7-52B26797122C")> _
Public Interface IFloatEntryTransaction _
    Inherits ICashTenderCountTransaction, IPosTransaction, IPosTransactionV1, IPosTransactionV2,  _
    IPosTransactionV3, ICashTenderCountTransactionV1
'Usage
Dim instance As IFloatEntryTransaction
```

``` csharp
[GuidAttribute("E87104E0-6CA0-41E2-AFF7-52B26797122C")]
public interface IFloatEntryTransaction : ICashTenderCountTransaction, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3, ICashTenderCountTransactionV1
```

``` c++
[GuidAttribute(L"E87104E0-6CA0-41E2-AFF7-52B26797122C")]
public interface class IFloatEntryTransaction : ICashTenderCountTransaction, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3, ICashTenderCountTransactionV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

