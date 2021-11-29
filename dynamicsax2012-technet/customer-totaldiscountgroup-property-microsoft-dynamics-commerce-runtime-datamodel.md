---
title: Customer.TotalDiscountGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.TotalDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.totaldiscountgroup(v=AX.60)
ms:contentKeyID: 62212721
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.TotalDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# TotalDiscountGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total discount group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ENDDISC")> _
<DataMemberAttribute> _
Public Property TotalDiscountGroup As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.TotalDiscountGroup

instance.TotalDiscountGroup = value
```

``` csharp
[ColumnAttribute("ENDDISC")]
[DataMemberAttribute]
public string TotalDiscountGroup { get; set; }
```

``` c++
[ColumnAttribute(L"ENDDISC")]
[DataMemberAttribute]
public:
property String^ TotalDiscountGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The total discount group.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

