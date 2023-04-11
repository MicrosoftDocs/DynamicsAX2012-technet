---
title: EmployeePermissions.AllowChangePeripheralStation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowChangePeripheralStation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowChangePeripheralStation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowchangeperipheralstation(v=AX.60)
ms:contentKeyID: 62214983
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowChangePeripheralStation
dev_langs:
- CSharp
- C++
- VB
---

# AllowChangePeripheralStation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether changing the peripheral station is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<ColumnAttribute("ALLOWCHANGEPERIPHERALSTATION")> _
<IgnoreDataMemberAttribute> _
Public Property AllowChangePeripheralStation As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowChangePeripheralStation

instance.AllowChangePeripheralStation = value
```

``` csharp
[RequiredAttribute]
[ColumnAttribute("ALLOWCHANGEPERIPHERALSTATION")]
[IgnoreDataMemberAttribute]
public bool AllowChangePeripheralStation { get; set; }
```

``` c++
[RequiredAttribute]
[ColumnAttribute(L"ALLOWCHANGEPERIPHERALSTATION")]
[IgnoreDataMemberAttribute]
public:
property bool AllowChangePeripheralStation {
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

