---
title: GlobalCustomer.CustomerType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.CustomerType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.globalcustomer.customertype(v=AX.60)
ms:contentKeyID: 62206740
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.CustomerType
dev_langs:
- CSharp
- C++
- VB
---

# CustomerType Property

Gets customer type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CUSTOMERTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property CustomerType As CustomerType
    Get
    Friend Set
'Usage
Dim instance As GlobalCustomer
Dim value As CustomerType

value = instance.CustomerType
```

``` csharp
[ColumnAttribute("CUSTOMERTYPE")]
[IgnoreDataMemberAttribute]
public CustomerType CustomerType { get; internal set; }
```

``` c++
[ColumnAttribute(L"CUSTOMERTYPE")]
[IgnoreDataMemberAttribute]
public:
property CustomerType CustomerType {
    CustomerType get ();
    internal: void set (CustomerType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerType](customertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the customer.  

## See Also

#### Reference

[GlobalCustomer Class](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

