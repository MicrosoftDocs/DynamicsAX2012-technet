---
title: TaxLineIndia.TaxItemGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxItemGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxItemGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.taxitemgroup(v=AX.60)
ms:contentKeyID: 62206186
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# TaxItemGroup Property

Gets or sets tax item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXITEMGROUP")> _
Public Property TaxItemGroup As String
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As String

value = instance.TaxItemGroup

instance.TaxItemGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXITEMGROUP")]
public string TaxItemGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXITEMGROUP")]
public:
property String^ TaxItemGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

