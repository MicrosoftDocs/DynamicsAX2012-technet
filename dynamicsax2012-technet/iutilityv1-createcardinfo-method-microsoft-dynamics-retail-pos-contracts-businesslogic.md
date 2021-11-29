---
title: IUtilityV1.CreateCardInfo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateCardInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.CreateCardInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.createcardinfo(v=AX.60)
ms:contentKeyID: 47128970
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.CreateCardInfo
dev_langs:
- CSharp
- C++
- VB
---

# CreateCardInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates an [ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) object.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateCardInfo As ICardInfo
'Usage
Dim instance As IUtilityV1
Dim returnValue As ICardInfo

returnValue = instance.CreateCardInfo()
```

``` csharp
ICardInfo CreateCardInfo()
```

``` c++
ICardInfo^ CreateCardInfo()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The card info.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

