---
title: ICashDrawerV1.CapStatus Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CapStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawerV1.CapStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icashdrawerv1.capstatus(v=AX.60)
ms:contentKeyID: 47344199
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawerV1.CapStatus
dev_langs:
- CSharp
- C++
- VB
---

# CapStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks if the cash drawer is capable of reporting back whether it is closed or open.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CapStatus As Boolean
'Usage
Dim instance As ICashDrawerV1
Dim returnValue As Boolean

returnValue = instance.CapStatus()
```

``` csharp
bool CapStatus()
```

``` c++
bool CapStatus()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if capable; otherwise, false.  

## See Also

#### Reference

[ICashDrawerV1 Interface](icashdrawerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

