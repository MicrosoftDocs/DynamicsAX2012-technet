---
title: ISaleLineItemV1.OrderLineRecordId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: OrderLineRecordId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.OrderLineRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.orderlinerecordid(v=AX.60)
ms:contentKeyID: 49843768
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.OrderLineRecordId
dev_langs:
- CSharp
- C++
- VB
---

# OrderLineRecordId Property

A RecId from AX

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property OrderLineRecordId As Long
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Long

value = instance.OrderLineRecordId

instance.OrderLineRecordId = value
```

``` csharp
long OrderLineRecordId { get; set; }
```

``` c++
property long long OrderLineRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

