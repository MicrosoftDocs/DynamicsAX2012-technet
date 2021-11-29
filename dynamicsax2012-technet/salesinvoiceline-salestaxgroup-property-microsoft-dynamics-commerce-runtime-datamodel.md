---
title: SalesInvoiceLine.SalesTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SalesTaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.salestaxgroup(v=AX.60)
ms:contentKeyID: 62210207
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SalesTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXGROUP")> _
<DataMemberAttribute> _
Public Property SalesTaxGroup As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.SalesTaxGroup

instance.SalesTaxGroup = value
```

``` csharp
[ColumnAttribute("TAXGROUP")]
[DataMemberAttribute]
public string SalesTaxGroup { get; set; }
```

``` c++
[ColumnAttribute(L"TAXGROUP")]
[DataMemberAttribute]
public:
property String^ SalesTaxGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The sales tax group.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

