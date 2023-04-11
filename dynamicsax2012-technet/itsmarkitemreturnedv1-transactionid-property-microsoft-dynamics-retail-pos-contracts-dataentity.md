---
title: ITSMarkItemReturnedV1.TransactionId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TransactionId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITSMarkItemReturnedV1.TransactionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itsmarkitemreturnedv1.transactionid(v=AX.60)
ms:contentKeyID: 47128218
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITSMarkItemReturnedV1.TransactionId
dev_langs:
- CSharp
- C++
- VB
---

# TransactionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the transaction ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TransactionId As String
    Get
    Set
'Usage
Dim instance As ITSMarkItemReturnedV1
Dim value As String

value = instance.TransactionId

instance.TransactionId = value
```

``` csharp
string TransactionId { get; set; }
```

``` c++
property String^ TransactionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ITSMarkItemReturnedV1 Interface](itsmarkitemreturnedv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

