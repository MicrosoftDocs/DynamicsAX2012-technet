---
title: IBarcodeInfoV1.MultiLineDiscountGroup Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: MultiLineDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.MultiLineDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.multilinediscountgroup(v=AX.60)
ms:contentKeyID: 47128414
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.MultiLineDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# MultiLineDiscountGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the multiline discount group.

The multiline discount group that the item is a part of.

The multiline discount group should be set when the item info is found.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MultiLineDiscountGroup As String
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
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

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

