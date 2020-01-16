---
title: Customer.CustomerGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CustomerGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.customergroup(v=AX.60)
ms:contentKeyID: 62210417
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CustomerGroup
dev_langs:
- CSharp
- C++
- VB
---

# CustomerGroup Property

Gets or sets the customer group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CUSTGROUP")> _
<DataMemberAttribute> _
Public Property CustomerGroup As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.CustomerGroup

instance.CustomerGroup = value
```

``` csharp
[ColumnAttribute("CUSTGROUP")]
[DataMemberAttribute]
public string CustomerGroup { get; set; }
```

``` c++
[ColumnAttribute(L"CUSTGROUP")]
[DataMemberAttribute]
public:
property String^ CustomerGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The customer group.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

