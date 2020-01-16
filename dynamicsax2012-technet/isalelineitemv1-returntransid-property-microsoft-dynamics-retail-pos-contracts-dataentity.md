---
title: ISaleLineItemV1.ReturnTransId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ReturnTransId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.ReturnTransId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.returntransid(v=AX.60)
ms:contentKeyID: 49829718
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.ReturnTransId
dev_langs:
- CSharp
- C++
- VB
---

# ReturnTransId Property

If the item is being returned (with a receipt) this field contains the id of the transaction the item was originally sold in.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ReturnTransId As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.ReturnTransId

instance.ReturnTransId = value
```

``` csharp
string ReturnTransId { get; set; }
```

``` c++
property String^ ReturnTransId {
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

