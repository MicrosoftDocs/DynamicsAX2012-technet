---
title: TaxOverride.DestinationItemTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DestinationItemTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.DestinationItemTaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxoverride.destinationitemtaxgroup(v=AX.60)
ms:contentKeyID: 62209898
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.DestinationItemTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# DestinationItemTaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the destination item tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DESTINATIONITEMTAXGROUP")> _
Public Property DestinationItemTaxGroup As String
    Get
    Set
'Usage
Dim instance As TaxOverride
Dim value As String

value = instance.DestinationItemTaxGroup

instance.DestinationItemTaxGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DESTINATIONITEMTAXGROUP")]
public string DestinationItemTaxGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DESTINATIONITEMTAXGROUP")]
public:
property String^ DestinationItemTaxGroup {
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

