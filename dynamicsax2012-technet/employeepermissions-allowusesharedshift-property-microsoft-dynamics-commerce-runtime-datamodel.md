---
title: EmployeePermissions.AllowUseSharedShift Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowUseSharedShift Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowUseSharedShift
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowusesharedshift(v=AX.60)
ms:contentKeyID: 65316276
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowUseSharedShift
dev_langs:
- CSharp
- C++
- VB
---

# AllowUseSharedShift Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ALLOWUSESHAREDSHIFT")> _
Public Property AllowUseSharedShift As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowUseSharedShift

instance.AllowUseSharedShift = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ALLOWUSESHAREDSHIFT")]
public bool AllowUseSharedShift { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ALLOWUSESHAREDSHIFT")]
public:
property bool AllowUseSharedShift {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

