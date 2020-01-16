---
title: ICashChangerV1.Regret Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Regret Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.Regret(Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerRegretType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icashchangerv1.regret(v=AX.60)
ms:contentKeyID: 47344240
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.Regret
dev_langs:
- CSharp
- C++
- VB
---

# Regret Method

Executes regret operation in the cash changer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Regret ( _
    regretType As CashChangerRegretType _
) As Boolean
'Usage
Dim instance As ICashChangerV1
Dim regretType As CashChangerRegretType
Dim returnValue As Boolean

returnValue = instance.Regret(regretType)
```

``` csharp
bool Regret(
    CashChangerRegretType regretType
)
```

``` c++
bool Regret(
    CashChangerRegretType regretType
)
```

#### Parameters

  - regretType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerRegretType](cashchangerregrettype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ICashChangerV1 Interface](icashchangerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

