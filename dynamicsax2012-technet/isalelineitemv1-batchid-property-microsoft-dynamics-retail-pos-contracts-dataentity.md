---
title: ISaleLineItemV1.BatchId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BatchId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.BatchId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.batchid(v=AX.60)
ms:contentKeyID: 49839991
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.BatchId
dev_langs:
- CSharp
- C++
- VB
---

# BatchId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The id of the batch which the item belongs to.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BatchId As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.BatchId

instance.BatchId = value
```

``` csharp
string BatchId { get; set; }
```

``` c++
property String^ BatchId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

