---
title: ISuspendRetrieveSystemV1.SuspendedTransactionCount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: SuspendedTransactionCount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV1.SuspendedTransactionCount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.isuspendretrievesystemv1.suspendedtransactioncount(v=AX.60)
ms:contentKeyID: 62205426
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV1.SuspendedTransactionCount
dev_langs:
- CSharp
- C++
- VB
---

# SuspendedTransactionCount Method

Amount of suspended transactions on the current terminal's store.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function SuspendedTransactionCount As Integer
'Usage
Dim instance As ISuspendRetrieveSystemV1
Dim returnValue As Integer

returnValue = instance.SuspendedTransactionCount()
```

``` csharp
int SuspendedTransactionCount()
```

``` c++
int SuspendedTransactionCount()
```

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The amount of suspended transaction  

## See Also

#### Reference

[ISuspendRetrieveSystemV1 Interface](isuspendretrievesystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

