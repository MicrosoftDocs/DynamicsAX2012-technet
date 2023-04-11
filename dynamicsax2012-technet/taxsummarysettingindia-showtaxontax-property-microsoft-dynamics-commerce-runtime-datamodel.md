---
title: TaxSummarySettingIndia.ShowTaxonTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShowTaxonTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxSummarySettingIndia.ShowTaxonTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxsummarysettingindia.showtaxontax(v=AX.60)
ms:contentKeyID: 62210640
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxSummarySettingIndia.ShowTaxonTax
dev_langs:
- CSharp
- C++
- VB
---

# ShowTaxonTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the tax code is calculated based on other tax codes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SHOWTAXONTAX")> _
Public Property ShowTaxonTax As Boolean
    Get
    Friend Set
'Usage
Dim instance As TaxSummarySettingIndia
Dim value As Boolean

value = instance.ShowTaxonTax
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SHOWTAXONTAX")]
public bool ShowTaxonTax { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SHOWTAXONTAX")]
public:
property bool ShowTaxonTax {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TaxSummarySettingIndia Class](taxsummarysettingindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

