---
title: SalesTaxGroup.TaxGroupName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxGroupName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTaxGroup.TaxGroupName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestaxgroup.taxgroupname(v=AX.60)
ms:contentKeyID: 62210210
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTaxGroup.TaxGroupName
dev_langs:
- CSharp
- C++
- VB
---

# TaxGroupName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the name of the tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXGROUPNAME")> _
Public Property TaxGroupName As String
    Get
    Friend Set
'Usage
Dim instance As SalesTaxGroup
Dim value As String

value = instance.TaxGroupName
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXGROUPNAME")]
public string TaxGroupName { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXGROUPNAME")]
public:
property String^ TaxGroupName {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name of the tax group.  

## See Also

#### Reference

[SalesTaxGroup Class](salestaxgroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

