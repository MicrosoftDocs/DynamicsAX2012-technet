---
title: Customer.MultilineDiscountGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MultilineDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.MultilineDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.multilinediscountgroup(v=AX.60)
ms:contentKeyID: 62207624
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.MultilineDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# MultilineDiscountGroup Property

Gets or sets the multiline discount group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MULTILINEDISC")> _
<DataMemberAttribute> _
Public Property MultilineDiscountGroup As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.MultilineDiscountGroup

instance.MultilineDiscountGroup = value
```

``` csharp
[ColumnAttribute("MULTILINEDISC")]
[DataMemberAttribute]
public string MultilineDiscountGroup { get; set; }
```

``` c++
[ColumnAttribute(L"MULTILINEDISC")]
[DataMemberAttribute]
public:
property String^ MultilineDiscountGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The multiline discount group.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

