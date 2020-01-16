---
title: ItemDimensions.GrossHeight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GrossHeight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions.GrossHeight
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemdimensions.grossheight(v=AX.60)
ms:contentKeyID: 49850326
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions.GrossHeight
dev_langs:
- CSharp
- C++
- VB
---

# GrossHeight Property

Gets the gross height.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("GROSSHEIGHT")> _
Public Property GrossHeight As Decimal
    Get
    Friend Set
'Usage
Dim instance As ItemDimensions
Dim value As Decimal

value = instance.GrossHeight
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("GROSSHEIGHT")]
public decimal GrossHeight { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"GROSSHEIGHT")]
public:
property Decimal GrossHeight {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ItemDimensions Class](itemdimensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

