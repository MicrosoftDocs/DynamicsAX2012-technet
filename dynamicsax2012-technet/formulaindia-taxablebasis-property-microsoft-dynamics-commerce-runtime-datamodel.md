---
title: FormulaIndia.TaxableBasis Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxableBasis Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.TaxableBasis
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.formulaindia.taxablebasis(v=AX.60)
ms:contentKeyID: 62207633
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.TaxableBasis
dev_langs:
- CSharp
- C++
- VB
---

# TaxableBasis Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax basis.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXABLEBASIS")> _
Public Property TaxableBasis As TaxableBasisIndia
    Get
    Friend Set
'Usage
Dim instance As FormulaIndia
Dim value As TaxableBasisIndia

value = instance.TaxableBasis
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXABLEBASIS")]
public TaxableBasisIndia TaxableBasis { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXABLEBASIS")]
public:
property TaxableBasisIndia TaxableBasis {
    TaxableBasisIndia get ();
    internal: void set (TaxableBasisIndia value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableBasisIndia](taxablebasisindia-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TaxableBasisIndia](taxablebasisindia-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[FormulaIndia Class](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

