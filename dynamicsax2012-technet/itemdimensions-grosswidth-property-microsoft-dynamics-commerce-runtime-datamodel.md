---
title: ItemDimensions.GrossWidth Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GrossWidth Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions.GrossWidth
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemdimensions.grosswidth(v=AX.60)
ms:contentKeyID: 49819630
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions.GrossWidth
dev_langs:
- CSharp
- C++
- VB
---

# GrossWidth Property

Gets the gross width.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("GROSSWIDTH")> _
<DataMemberAttribute> _
Public Property GrossWidth As Decimal
    Get
    Friend Set
'Usage
Dim instance As ItemDimensions
Dim value As Decimal

value = instance.GrossWidth
```

``` csharp
[ColumnAttribute("GROSSWIDTH")]
[DataMemberAttribute]
public decimal GrossWidth { get; internal set; }
```

``` c++
[ColumnAttribute(L"GROSSWIDTH")]
[DataMemberAttribute]
public:
property Decimal GrossWidth {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ItemDimensions Class](itemdimensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

