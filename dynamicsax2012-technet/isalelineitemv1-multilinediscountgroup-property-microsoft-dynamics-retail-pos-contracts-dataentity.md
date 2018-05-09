---
title: ISaleLineItemV1.MultiLineDiscountGroup Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: MultiLineDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.MultiLineDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.multilinediscountgroup(v=AX.60)
ms:contentKeyID: 49849392
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.MultiLineDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# MultiLineDiscountGroup Property

The multiline discount group that the item is a part of. Should be set when the item info is found.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MultiLineDiscountGroup As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.MultiLineDiscountGroup

instance.MultiLineDiscountGroup = value
```

``` csharp
string MultiLineDiscountGroup { get; set; }
```

``` c++
property String^ MultiLineDiscountGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

