---
title: EmployeePermissions.AllowKitDisassembly Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowKitDisassembly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowKitDisassembly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowkitdisassembly(v=AX.60)
ms:contentKeyID: 62205732
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowKitDisassembly
dev_langs:
- CSharp
- C++
- VB
---

# AllowKitDisassembly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether kit disassembly is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<ColumnAttribute("ALLOWKITDISASSEMBLY")> _
<IgnoreDataMemberAttribute> _
Public Property AllowKitDisassembly As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowKitDisassembly

instance.AllowKitDisassembly = value
```

``` csharp
[RequiredAttribute]
[ColumnAttribute("ALLOWKITDISASSEMBLY")]
[IgnoreDataMemberAttribute]
public bool AllowKitDisassembly { get; set; }
```

``` c++
[RequiredAttribute]
[ColumnAttribute(L"ALLOWKITDISASSEMBLY")]
[IgnoreDataMemberAttribute]
public:
property bool AllowKitDisassembly {
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

