---
title: ICashChangerV1.ConcludeTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ConcludeTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.ConcludeTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icashchangerv1.concludetransaction(v=AX.60)
ms:contentKeyID: 47343967
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.ConcludeTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ConcludeTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Concludes the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ConcludeTransaction ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICashChangerV1
Dim posTransaction As IPosTransaction

instance.ConcludeTransaction(posTransaction)
```

``` csharp
void ConcludeTransaction(
    IPosTransaction posTransaction
)
```

``` c++
void ConcludeTransaction(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICashChangerV1 Interface](icashchangerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

