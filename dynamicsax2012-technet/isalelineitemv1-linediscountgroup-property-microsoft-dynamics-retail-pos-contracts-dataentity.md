---
title: ISaleLineItemV1.LineDiscountGroup Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LineDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.LineDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.linediscountgroup(v=AX.60)
ms:contentKeyID: 49849035
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.LineDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscountGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The line discount group that the item belongs to. Should be set when the item info is found.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LineDiscountGroup As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.LineDiscountGroup

instance.LineDiscountGroup = value
```

``` csharp
string LineDiscountGroup { get; set; }
```

``` c++
property String^ LineDiscountGroup {
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

