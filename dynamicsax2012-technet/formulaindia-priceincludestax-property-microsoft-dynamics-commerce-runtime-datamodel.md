---
title: FormulaIndia.PriceIncludesTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceIncludesTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.PriceIncludesTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.formulaindia.priceincludestax(v=AX.60)
ms:contentKeyID: 62212231
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.PriceIncludesTax
dev_langs:
- CSharp
- C++
- VB
---

# PriceIncludesTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether it is price incl.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEINCLTAX")> _
<DataMemberAttribute> _
Public Property PriceIncludesTax As Boolean
    Get
    Friend Set
'Usage
Dim instance As FormulaIndia
Dim value As Boolean

value = instance.PriceIncludesTax
```

``` csharp
[ColumnAttribute("PRICEINCLTAX")]
[DataMemberAttribute]
public bool PriceIncludesTax { get; internal set; }
```

``` c++
[ColumnAttribute(L"PRICEINCLTAX")]
[DataMemberAttribute]
public:
property bool PriceIncludesTax {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[FormulaIndia Class](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

