---
title: EmployeePermissions.AllowCreateOrder Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowCreateOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowCreateOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowcreateorder(v=AX.60)
ms:contentKeyID: 62213641
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowCreateOrder
dev_langs:
- CSharp
- C++
- VB
---

# AllowCreateOrder Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether order creation is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ALLOWCREATEORDER")> _
Public Property AllowCreateOrder As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowCreateOrder

instance.AllowCreateOrder = value
```

``` csharp
[RequiredAttribute]
[IgnoreDataMemberAttribute]
[ColumnAttribute("ALLOWCREATEORDER")]
public bool AllowCreateOrder { get; set; }
```

``` c++
[RequiredAttribute]
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ALLOWCREATEORDER")]
public:
property bool AllowCreateOrder {
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

