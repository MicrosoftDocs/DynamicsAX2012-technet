---
title: ProductRules.CanQuantityBecomeNegative Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CanQuantityBecomeNegative Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.CanQuantityBecomeNegative
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.canquantitybecomenegative(v=AX.60)
ms:contentKeyID: 62210671
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.CanQuantityBecomeNegative
dev_langs:
- CSharp
- C++
- VB
---

# CanQuantityBecomeNegative Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the quantity associated with this product may be negative.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QTYBECOMESNEGATIVE")> _
Public Property CanQuantityBecomeNegative As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As Boolean

value = instance.CanQuantityBecomeNegative
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QTYBECOMESNEGATIVE")]
public bool CanQuantityBecomeNegative { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QTYBECOMESNEGATIVE")]
public:
property bool CanQuantityBecomeNegative {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

