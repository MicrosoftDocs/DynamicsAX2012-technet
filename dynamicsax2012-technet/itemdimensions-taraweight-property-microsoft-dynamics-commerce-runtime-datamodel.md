---
title: ItemDimensions.TaraWeight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaraWeight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions.TaraWeight
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemdimensions.taraweight(v=AX.60)
ms:contentKeyID: 65321309
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions.TaraWeight
dev_langs:
- CSharp
- C++
- VB
---

# TaraWeight Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TARAWEIGHT")> _
Public ReadOnly Property TaraWeight As Decimal
    Get
'Usage
Dim instance As ItemDimensions
Dim value As Decimal

value = instance.TaraWeight
```

``` csharp
[ColumnAttribute("TARAWEIGHT")]
public decimal TaraWeight { get; }
```

``` c++
[ColumnAttribute(L"TARAWEIGHT")]
public:
property Decimal TaraWeight {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[ItemDimensions Class](itemdimensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

