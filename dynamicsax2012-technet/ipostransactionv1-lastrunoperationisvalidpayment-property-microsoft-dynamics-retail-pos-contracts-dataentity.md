---
title: IPosTransactionV1.LastRunOperationIsValidPayment Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LastRunOperationIsValidPayment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.LastRunOperationIsValidPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.lastrunoperationisvalidpayment(v=AX.60)
ms:contentKeyID: 47129241
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.LastRunOperationIsValidPayment
dev_langs:
- CSharp
- C++
- VB
---

# LastRunOperationIsValidPayment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets whether the last run operation was a valid payment operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property LastRunOperationIsValidPayment As Boolean
    Get
'Usage
Dim instance As IPosTransactionV1
Dim value As Boolean

value = instance.LastRunOperationIsValidPayment
```

``` csharp
bool LastRunOperationIsValidPayment { get; }
```

``` c++
property bool LastRunOperationIsValidPayment {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

