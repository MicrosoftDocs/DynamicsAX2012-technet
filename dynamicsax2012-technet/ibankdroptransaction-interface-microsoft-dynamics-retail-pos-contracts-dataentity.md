---
title: IBankDropTransaction Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IBankDropTransaction Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBankDropTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibankdroptransaction(v=AX.60)
ms:contentKeyID: 49849078
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBankDropTransaction
dev_langs:
- CSharp
- C++
- VB
---

# IBankDropTransaction Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

IBankDropTransaction interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("020741AC-D356-4DB6-9F79-D8C7E2B81595")> _
Public Interface IBankDropTransaction _
    Inherits ITenderCountTransaction, ITenderCountTransactionV1, IPosTransaction, IPosTransactionV1,  _
    IPosTransactionV2, IPosTransactionV3, IBankDropTransactionV1
'Usage
Dim instance As IBankDropTransaction
```

``` csharp
[GuidAttribute("020741AC-D356-4DB6-9F79-D8C7E2B81595")]
public interface IBankDropTransaction : ITenderCountTransaction, 
    ITenderCountTransactionV1, IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3, 
    IBankDropTransactionV1
```

``` c++
[GuidAttribute(L"020741AC-D356-4DB6-9F79-D8C7E2B81595")]
public interface class IBankDropTransaction : ITenderCountTransaction, 
    ITenderCountTransactionV1, IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3, 
    IBankDropTransactionV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

