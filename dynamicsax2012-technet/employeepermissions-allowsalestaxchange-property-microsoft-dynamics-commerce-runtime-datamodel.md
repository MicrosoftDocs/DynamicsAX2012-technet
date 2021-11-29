---
title: EmployeePermissions.AllowSalesTaxChange Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowSalesTaxChange Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowSalesTaxChange
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowsalestaxchange(v=AX.60)
ms:contentKeyID: 62207226
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowSalesTaxChange
dev_langs:
- CSharp
- C++
- VB
---

# AllowSalesTaxChange Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether changes to sales tax is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("ALLOWSALESTAXCHANGE")> _
Public Property AllowSalesTaxChange As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowSalesTaxChange

instance.AllowSalesTaxChange = value
```

``` csharp
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("ALLOWSALESTAXCHANGE")]
public bool AllowSalesTaxChange { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"ALLOWSALESTAXCHANGE")]
public:
property bool AllowSalesTaxChange {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

