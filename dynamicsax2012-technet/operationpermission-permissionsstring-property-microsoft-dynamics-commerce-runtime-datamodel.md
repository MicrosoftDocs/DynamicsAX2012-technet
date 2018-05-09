---
title: OperationPermission.PermissionsString Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PermissionsString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.PermissionsString
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.operationpermission.permissionsstring(v=AX.60)
ms:contentKeyID: 65320120
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.PermissionsString
dev_langs:
- CSharp
- C++
- VB
---

# PermissionsString Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PERMISSIONNAME")> _
<IgnoreDataMemberAttribute> _
Public Property PermissionsString As String
    Get
    Set
'Usage
Dim instance As OperationPermission
Dim value As String

value = instance.PermissionsString

instance.PermissionsString = value
```

``` csharp
[ColumnAttribute("PERMISSIONNAME")]
[IgnoreDataMemberAttribute]
public string PermissionsString { get; set; }
```

``` c++
[ColumnAttribute(L"PERMISSIONNAME")]
[IgnoreDataMemberAttribute]
public:
property String^ PermissionsString {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[OperationPermission Class](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

