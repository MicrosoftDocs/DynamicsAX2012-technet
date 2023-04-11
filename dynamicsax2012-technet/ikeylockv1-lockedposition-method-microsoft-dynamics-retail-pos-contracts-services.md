---
title: IKeyLockV1.LockedPosition Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: LockedPosition Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IKeyLockV1.LockedPosition
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ikeylockv1.lockedposition(v=AX.60)
ms:contentKeyID: 47343849
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IKeyLockV1.LockedPosition
dev_langs:
- CSharp
- C++
- VB
---

# LockedPosition Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks if the key is in the locked position.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function LockedPosition As Boolean
'Usage
Dim instance As IKeyLockV1
Dim returnValue As Boolean

returnValue = instance.LockedPosition()
```

``` csharp
bool LockedPosition()
```

``` c++
bool LockedPosition()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if locked position; otherwise, false.  

## See Also

#### Reference

[IKeyLockV1 Interface](ikeylockv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

