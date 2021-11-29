---
title: SalesTaxGroup.TaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTaxGroup.TaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestaxgroup.taxgroup(v=AX.60)
ms:contentKeyID: 62206390
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTaxGroup.TaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# TaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXGROUP")> _
<DataMemberAttribute> _
Public Property TaxGroup As String
    Get
    Friend Set
'Usage
Dim instance As SalesTaxGroup
Dim value As String

value = instance.TaxGroup
```

``` csharp
[ColumnAttribute("TAXGROUP")]
[DataMemberAttribute]
public string TaxGroup { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXGROUP")]
[DataMemberAttribute]
public:
property String^ TaxGroup {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tax group.  

## See Also

#### Reference

[SalesTaxGroup Class](salestaxgroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

