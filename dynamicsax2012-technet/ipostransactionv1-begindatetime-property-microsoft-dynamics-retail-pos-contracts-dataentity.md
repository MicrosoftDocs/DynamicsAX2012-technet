---
title: IPosTransactionV1.BeginDateTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BeginDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.BeginDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.begindatetime(v=AX.60)
ms:contentKeyID: 47129311
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.BeginDateTime
dev_langs:
- CSharp
- C++
- VB
---

# BeginDateTime Property

Gets the start date and time of the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property BeginDateTime As DateTime
    Get
'Usage
Dim instance As IPosTransactionV1
Dim value As DateTime

value = instance.BeginDateTime
```

``` csharp
DateTime BeginDateTime { get; }
```

``` c++
property DateTime BeginDateTime {
    DateTime get ();
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
The [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

