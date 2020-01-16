---
title: ChargeConfiguration.ItemTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ItemTaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.itemtaxgroup(v=AX.60)
ms:contentKeyID: 49854454
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ItemTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# ItemTaxGroup Property

Gets or sets the item tax group on the configuration's charge code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ITEMTAXGROUP")> _
<DataMemberAttribute> _
Public Property ItemTaxGroup As String
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As String

value = instance.ItemTaxGroup

instance.ItemTaxGroup = value
```

``` csharp
[ColumnAttribute("ITEMTAXGROUP")]
[DataMemberAttribute]
public string ItemTaxGroup { get; set; }
```

``` c++
[ColumnAttribute(L"ITEMTAXGROUP")]
[DataMemberAttribute]
public:
property String^ ItemTaxGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

