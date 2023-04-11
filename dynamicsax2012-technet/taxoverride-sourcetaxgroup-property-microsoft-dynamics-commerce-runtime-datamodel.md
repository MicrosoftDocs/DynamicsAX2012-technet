---
title: TaxOverride.SourceTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SourceTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.SourceTaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxoverride.sourcetaxgroup(v=AX.60)
ms:contentKeyID: 62210108
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.SourceTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# SourceTaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the source tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SOURCETAXGROUP")> _
<DataMemberAttribute> _
Public Property SourceTaxGroup As String
    Get
    Set
'Usage
Dim instance As TaxOverride
Dim value As String

value = instance.SourceTaxGroup

instance.SourceTaxGroup = value
```

``` csharp
[ColumnAttribute("SOURCETAXGROUP")]
[DataMemberAttribute]
public string SourceTaxGroup { get; set; }
```

``` c++
[ColumnAttribute(L"SOURCETAXGROUP")]
[DataMemberAttribute]
public:
property String^ SourceTaxGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxOverride Class](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

