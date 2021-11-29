---
title: IRetailTransactionV1.RefundReceiptId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RefundReceiptId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.RefundReceiptId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.refundreceiptid(v=AX.60)
ms:contentKeyID: 49841407
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.RefundReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# RefundReceiptId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Id of a receiption for items that will be refunded.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RefundReceiptId As String
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As String

value = instance.RefundReceiptId

instance.RefundReceiptId = value
```

``` csharp
string RefundReceiptId { get; set; }
```

``` c++
property String^ RefundReceiptId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

