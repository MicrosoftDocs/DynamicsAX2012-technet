---
title: IApplicationV1.TransactionServices Property  (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: TransactionServices Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.TransactionServices
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.iapplicationv1.transactionservices(v=AX.60)
ms:contentKeyID: 47128194
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.TransactionServices
dev_langs:
- CSharp
- C++
- VB
---

# TransactionServices Property

Gets the transaction services.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TransactionServices As ITransactionServices
    Get
'Usage
Dim instance As IApplicationV1
Dim value As ITransactionServices

value = instance.TransactionServices
```

``` csharp
ITransactionServices TransactionServices { get; }
```

``` c++
property ITransactionServices^ TransactionServices {
    ITransactionServices^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServices](itransactionservices-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)  
The \[T:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices. \] value.  

## See Also

#### Reference

[IApplicationV1 Interface](iapplicationv1-interface-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

