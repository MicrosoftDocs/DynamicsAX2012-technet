---
title: Customer.MiddleName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MiddleName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.MiddleName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.middlename(v=AX.60)
ms:contentKeyID: 49854019
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.MiddleName
dev_langs:
- CSharp
- C++
- VB
---

# MiddleName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer middle name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MIDDLENAME")> _
<DataMemberAttribute> _
Public Property MiddleName As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.MiddleName

instance.MiddleName = value
```

``` csharp
[ColumnAttribute("MIDDLENAME")]
[DataMemberAttribute]
public string MiddleName { get; set; }
```

``` c++
[ColumnAttribute(L"MIDDLENAME")]
[DataMemberAttribute]
public:
property String^ MiddleName {
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

