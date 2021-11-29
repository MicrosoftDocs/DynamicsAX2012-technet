---
title: TaxableItem.SalesTaxGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTaxGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.SalesTaxGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.salestaxgroupid(v=AX.60)
ms:contentKeyID: 49841934
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.SalesTaxGroupId
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales tax group id for this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESTAXGROUPID")> _
Public Property SalesTaxGroupId As String
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As String

value = instance.SalesTaxGroupId

instance.SalesTaxGroupId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESTAXGROUPID")]
public string SalesTaxGroupId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESTAXGROUPID")]
public:
property String^ SalesTaxGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

