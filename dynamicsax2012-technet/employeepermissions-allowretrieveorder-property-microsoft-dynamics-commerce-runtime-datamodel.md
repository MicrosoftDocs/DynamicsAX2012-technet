---
title: EmployeePermissions.AllowRetrieveOrder Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowRetrieveOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowRetrieveOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowretrieveorder(v=AX.60)
ms:contentKeyID: 62208433
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowRetrieveOrder
dev_langs:
- CSharp
- C++
- VB
---

# AllowRetrieveOrder Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether order retrieval is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ALLOWRETRIEVEORDER")> _
Public Property AllowRetrieveOrder As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowRetrieveOrder

instance.AllowRetrieveOrder = value
```

``` csharp
[RequiredAttribute]
[IgnoreDataMemberAttribute]
[ColumnAttribute("ALLOWRETRIEVEORDER")]
public bool AllowRetrieveOrder { get; set; }
```

``` c++
[RequiredAttribute]
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ALLOWRETRIEVEORDER")]
public:
property bool AllowRetrieveOrder {
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

