---
title: IEFTInfoV1.ExternalCardReceipts Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ExternalCardReceipts Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.ExternalCardReceipts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.externalcardreceipts(v=AX.60)
ms:contentKeyID: 47128081
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.ExternalCardReceipts
dev_langs:
- CSharp
- C++
- VB
---

# ExternalCardReceipts Property

A list of card receipts acquired from an external EFT terminal that are to be printed at the end of the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ExternalCardReceipts As LinkedList(Of String)
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As LinkedList(Of String)

value = instance.ExternalCardReceipts

instance.ExternalCardReceipts = value
```

``` csharp
LinkedList<string> ExternalCardReceipts { get; set; }
```

``` c++
property LinkedList<String^>^ ExternalCardReceipts {
    LinkedList<String^>^ get ();
    void set (LinkedList<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.LinkedList](https://technet.microsoft.com/library/he2s3bh7\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
The [System.Collections.Generic.LinkedList\<T\>](https://technet.microsoft.com/library/he2s3bh7\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

