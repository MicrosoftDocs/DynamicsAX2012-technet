---
title: Customer.CustomerType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CustomerType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.customertype(v=AX.60)
ms:contentKeyID: 49856282
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CustomerType
dev_langs:
- CSharp
- C++
- VB
---

# CustomerType Property

Gets or sets the customer type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INSTANCERELATIONTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property CustomerType As CustomerType
    Get
    Set
'Usage
Dim instance As Customer
Dim value As CustomerType

value = instance.CustomerType

instance.CustomerType = value
```

``` csharp
[ColumnAttribute("INSTANCERELATIONTYPE")]
[IgnoreDataMemberAttribute]
public CustomerType CustomerType { get; set; }
```

``` c++
[ColumnAttribute(L"INSTANCERELATIONTYPE")]
[IgnoreDataMemberAttribute]
public:
property CustomerType CustomerType {
    CustomerType get ();
    void set (CustomerType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerType](customertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the customer.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

