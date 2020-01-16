---
title: PriceAdjustmentPriceLine.IsCompoundable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCompoundable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustmentPriceLine.IsCompoundable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustmentpriceline.iscompoundable(v=AX.60)
ms:contentKeyID: 62209714
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustmentPriceLine.IsCompoundable
dev_langs:
- CSharp
- C++
- VB
---

# IsCompoundable Property

Gets or sets a value indicating whether the price adjustment line can combine with other lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISCOMPOUNDABLE")> _
Public Property IsCompoundable As Boolean
    Get
    Set
'Usage
Dim instance As PriceAdjustmentPriceLine
Dim value As Boolean

value = instance.IsCompoundable

instance.IsCompoundable = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISCOMPOUNDABLE")]
public bool IsCompoundable { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISCOMPOUNDABLE")]
public:
property bool IsCompoundable {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PriceAdjustmentPriceLine Class](priceadjustmentpriceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

