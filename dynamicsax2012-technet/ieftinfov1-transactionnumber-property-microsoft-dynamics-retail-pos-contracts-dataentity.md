---
title: IEFTInfoV1.TransactionNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TransactionNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.TransactionNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.transactionnumber(v=AX.60)
ms:contentKeyID: 47128427
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.TransactionNumber
dev_langs:
- CSharp
- C++
- VB
---

# TransactionNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

For a normal transaction, the transaction number can be read after the transaction.

If this is a void transaction, this property must contain the transaction number to void.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TransactionNumber As Integer
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As Integer

value = instance.TransactionNumber

instance.TransactionNumber = value
```

``` csharp
int TransactionNumber { get; set; }
```

``` c++
property int TransactionNumber {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

