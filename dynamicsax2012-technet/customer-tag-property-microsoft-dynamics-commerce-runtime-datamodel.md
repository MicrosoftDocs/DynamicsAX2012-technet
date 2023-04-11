---
title: Customer.Tag Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Tag Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Tag
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.tag(v=AX.60)
ms:contentKeyID: 62212018
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Tag
dev_langs:
- CSharp
- C++
- VB
---

# Tag Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value for tag.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAG")> _
<DataMemberAttribute> _
Public Property Tag As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.Tag

instance.Tag = value
```

``` csharp
[ColumnAttribute("TAG")]
[DataMemberAttribute]
public string Tag { get; set; }
```

``` c++
[ColumnAttribute(L"TAG")]
[DataMemberAttribute]
public:
property String^ Tag {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

