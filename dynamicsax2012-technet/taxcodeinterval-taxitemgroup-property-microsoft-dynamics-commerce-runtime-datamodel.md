---
title: TaxCodeInterval.TaxItemGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxItemGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxItemGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxitemgroup(v=AX.60)
ms:contentKeyID: 62208565
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# TaxItemGroup Property

Gets the tax item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXITEMGROUP")> _
Public Property TaxItemGroup As String
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As String

value = instance.TaxItemGroup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXITEMGROUP")]
public string TaxItemGroup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXITEMGROUP")]
public:
property String^ TaxItemGroup {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

