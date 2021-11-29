---
title: ItemUnitConversion.IsNop Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsNop Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion.IsNop
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemunitconversion.isnop(v=AX.60)
ms:contentKeyID: 49823935
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion.IsNop
dev_langs:
- CSharp
- C++
- VB
---

# IsNop Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the conversion effectively does nothing at all.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property IsNop As Boolean
    Get
'Usage
Dim instance As ItemUnitConversion
Dim value As Boolean

value = instance.IsNop
```

``` csharp
public bool IsNop { get; }
```

``` c++
public:
property bool IsNop {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true the conversion effectively does nothing at all; otherwise, false.  

## See Also

#### Reference

[ItemUnitConversion Class](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

