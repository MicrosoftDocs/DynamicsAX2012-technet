---
title: IPosTransactionV2.LastRunOperationIsValidPayment Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LastRunOperationIsValidPayment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.LastRunOperationIsValidPayment
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv2.lastrunoperationisvalidpayment(v=AX.60)
ms:contentKeyID: 49856223
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.LastRunOperationIsValidPayment
dev_langs:
- CSharp
- C++
- VB
---

# LastRunOperationIsValidPayment Property

If the last run operation was a valid payment operation, that is a successful one.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
WriteOnly Property LastRunOperationIsValidPayment As Boolean
    Set
'Usage
Dim instance As IPosTransactionV2
Dim value As Boolean

instance.LastRunOperationIsValidPayment = value
```

``` csharp
bool LastRunOperationIsValidPayment { set; }
```

``` c++
property bool LastRunOperationIsValidPayment {
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IPosTransactionV2 Interface](ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

