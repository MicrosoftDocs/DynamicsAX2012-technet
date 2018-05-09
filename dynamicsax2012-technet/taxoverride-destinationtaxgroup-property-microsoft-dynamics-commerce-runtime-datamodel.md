---
title: TaxOverride.DestinationTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DestinationTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.DestinationTaxGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxoverride.destinationtaxgroup(v=AX.60)
ms:contentKeyID: 62212731
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.DestinationTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# DestinationTaxGroup Property

Gets or sets the destination tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DESTINATIONTAXGROUP")> _
Public Property DestinationTaxGroup As String
    Get
    Set
'Usage
Dim instance As TaxOverride
Dim value As String

value = instance.DestinationTaxGroup

instance.DestinationTaxGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DESTINATIONTAXGROUP")]
public string DestinationTaxGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DESTINATIONTAXGROUP")]
public:
property String^ DestinationTaxGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxOverride Class](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

