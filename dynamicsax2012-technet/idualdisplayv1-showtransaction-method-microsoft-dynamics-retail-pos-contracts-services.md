---
title: IDualDisplayV1.ShowTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ShowTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDualDisplayV1.ShowTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idualdisplayv1.showtransaction(v=AX.60)
ms:contentKeyID: 47344396
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDualDisplayV1.ShowTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ShowTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Show transaction on the dual display.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ShowTransaction ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IDualDisplayV1
Dim posTransaction As IPosTransaction

instance.ShowTransaction(posTransaction)
```

``` csharp
void ShowTransaction(
    IPosTransaction posTransaction
)
```

``` c++
void ShowTransaction(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IDualDisplayV1 Interface](idualdisplayv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

