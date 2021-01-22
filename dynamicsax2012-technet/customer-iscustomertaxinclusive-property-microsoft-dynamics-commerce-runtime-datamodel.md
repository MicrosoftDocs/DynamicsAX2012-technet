---
title: Customer.IsCustomerTaxInclusive Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCustomerTaxInclusive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.IsCustomerTaxInclusive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.iscustomertaxinclusive(v=AX.60)
ms:contentKeyID: 49821283
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.IsCustomerTaxInclusive
dev_langs:
- CSharp
- C++
- VB
---

# IsCustomerTaxInclusive Property

Gets or sets a value indicating whether this customer is tax inclusive.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INCLTAX")> _
Public Property IsCustomerTaxInclusive As Boolean
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Boolean

value = instance.IsCustomerTaxInclusive

instance.IsCustomerTaxInclusive = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INCLTAX")]
public bool IsCustomerTaxInclusive { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INCLTAX")]
public:
property bool IsCustomerTaxInclusive {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

