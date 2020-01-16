---
title: ISuspendRetrieveSystemV1.RetrieveTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: RetrieveTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV1.RetrieveTransaction(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.isuspendretrievesystemv1.retrievetransaction(v=AX.60)
ms:contentKeyID: 62204280
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV1.RetrieveTransaction
dev_langs:
- CSharp
- C++
- VB
---

# RetrieveTransaction Method

Retrieves the transacation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RetrieveTransaction ( _
    suspendedTransactionId As String _
) As IPosTransaction
'Usage
Dim instance As ISuspendRetrieveSystemV1
Dim suspendedTransactionId As String
Dim returnValue As IPosTransaction

returnValue = instance.RetrieveTransaction(suspendedTransactionId)
```

``` csharp
IPosTransaction RetrieveTransaction(
    string suspendedTransactionId
)
```

``` c++
IPosTransaction^ RetrieveTransaction(
    String^ suspendedTransactionId
)
```

#### Parameters

  - suspendedTransactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The transaction.  

## See Also

#### Reference

[ISuspendRetrieveSystemV1 Interface](isuspendretrievesystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

