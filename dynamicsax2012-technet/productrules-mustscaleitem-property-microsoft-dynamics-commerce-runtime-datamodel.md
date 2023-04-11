---
title: ProductRules.MustScaleItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MustScaleItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.MustScaleItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.mustscaleitem(v=AX.60)
ms:contentKeyID: 62214056
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.MustScaleItem
dev_langs:
- CSharp
- C++
- VB
---

# MustScaleItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether this product requires weighing.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SCALEITEM")> _
<DataMemberAttribute> _
Public Property MustScaleItem As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As Boolean

value = instance.MustScaleItem
```

``` csharp
[ColumnAttribute("SCALEITEM")]
[DataMemberAttribute]
public bool MustScaleItem { get; internal set; }
```

``` c++
[ColumnAttribute(L"SCALEITEM")]
[DataMemberAttribute]
public:
property bool MustScaleItem {
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

