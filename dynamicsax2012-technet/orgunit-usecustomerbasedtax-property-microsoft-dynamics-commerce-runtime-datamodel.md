---
title: OrgUnit.UseCustomerBasedTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseCustomerBasedTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.UseCustomerBasedTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.usecustomerbasedtax(v=AX.60)
ms:contentKeyID: 62212619
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.UseCustomerBasedTax
dev_langs:
- CSharp
- C++
- VB
---

# UseCustomerBasedTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether customer based tax is used.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("USECUSTOMERBASEDTAX")> _
<DataMemberAttribute> _
Public Property UseCustomerBasedTax As Boolean
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As Boolean

value = instance.UseCustomerBasedTax

instance.UseCustomerBasedTax = value
```

``` csharp
[ColumnAttribute("USECUSTOMERBASEDTAX")]
[DataMemberAttribute]
public bool UseCustomerBasedTax { get; set; }
```

``` c++
[ColumnAttribute(L"USECUSTOMERBASEDTAX")]
[DataMemberAttribute]
public:
property bool UseCustomerBasedTax {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

