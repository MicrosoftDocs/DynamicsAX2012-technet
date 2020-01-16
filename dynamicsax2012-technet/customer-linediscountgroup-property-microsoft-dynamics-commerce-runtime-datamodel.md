---
title: Customer.LineDiscountGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.LineDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.linediscountgroup(v=AX.60)
ms:contentKeyID: 62211026
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.LineDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscountGroup Property

Gets or sets the line discount group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEDISC")> _
Public Property LineDiscountGroup As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.LineDiscountGroup

instance.LineDiscountGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEDISC")]
public string LineDiscountGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEDISC")]
public:
property String^ LineDiscountGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The line discount group.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

