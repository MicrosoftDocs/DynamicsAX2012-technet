---
title: IUtilityV2.CreateLogOnOffTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateLogOnOffTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateLogOnOffTransaction(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createlogonofftransaction(v=AX.60)
ms:contentKeyID: 49849071
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateLogOnOffTransaction
dev_langs:
- CSharp
- C++
- VB
---

# CreateLogOnOffTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateLogOnOffTransaction ( _
    isLogOn As Boolean _
) As ILogOnOffTransaction
'Usage
Dim instance As IUtilityV2
Dim isLogOn As Boolean
Dim returnValue As ILogOnOffTransaction

returnValue = instance.CreateLogOnOffTransaction(isLogOn)
```

``` csharp
ILogOnOffTransaction CreateLogOnOffTransaction(
    bool isLogOn
)
```

``` c++
ILogOnOffTransaction^ CreateLogOnOffTransaction(
    bool isLogOn
)
```

#### Parameters

  - isLogOn  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILogOnOffTransaction](ilogonofftransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

