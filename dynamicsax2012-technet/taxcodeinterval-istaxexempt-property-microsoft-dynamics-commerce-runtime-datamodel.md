---
title: TaxCodeInterval.IsTaxExempt Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsTaxExempt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.IsTaxExempt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.istaxexempt(v=AX.60)
ms:contentKeyID: 62214257
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.IsTaxExempt
dev_langs:
- CSharp
- C++
- VB
---

# IsTaxExempt Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether tax is exempt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EXEMPTTAX")> _
Public Property IsTaxExempt As Boolean
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Boolean

value = instance.IsTaxExempt
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EXEMPTTAX")]
public bool IsTaxExempt { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EXEMPTTAX")]
public:
property bool IsTaxExempt {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

