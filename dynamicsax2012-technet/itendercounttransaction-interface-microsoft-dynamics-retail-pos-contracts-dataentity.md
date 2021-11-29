---
title: ITenderCountTransaction Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ITenderCountTransaction Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderCountTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itendercounttransaction(v=AX.60)
ms:contentKeyID: 49856232
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderCountTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ITenderCountTransaction Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

ITenderCountTransaction interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("2970B332-319C-4B0F-A070-A6294B85F3B1")> _
Public Interface ITenderCountTransaction _
    Inherits ITenderCountTransactionV1, IPosTransaction, IPosTransactionV1, IPosTransactionV2,  _
    IPosTransactionV3
'Usage
Dim instance As ITenderCountTransaction
```

``` csharp
[GuidAttribute("2970B332-319C-4B0F-A070-A6294B85F3B1")]
public interface ITenderCountTransaction : ITenderCountTransactionV1, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3
```

``` c++
[GuidAttribute(L"2970B332-319C-4B0F-A070-A6294B85F3B1")]
public interface class ITenderCountTransaction : ITenderCountTransactionV1, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

