---
title: IEFTInfoV1.TransactionDateTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TransactionDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.TransactionDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.transactiondatetime(v=AX.60)
ms:contentKeyID: 47128601
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.TransactionDateTime
dev_langs:
- CSharp
- C++
- VB
---

# TransactionDateTime Property

The date and time of the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TransactionDateTime As DateTime
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As DateTime

value = instance.TransactionDateTime

instance.TransactionDateTime = value
```

``` csharp
DateTime TransactionDateTime { get; set; }
```

``` c++
property DateTime TransactionDateTime {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
The [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

