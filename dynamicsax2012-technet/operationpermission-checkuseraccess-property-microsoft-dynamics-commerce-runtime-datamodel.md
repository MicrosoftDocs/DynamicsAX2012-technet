---
title: OperationPermission.CheckUserAccess Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CheckUserAccess Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.CheckUserAccess
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.operationpermission.checkuseraccess(v=AX.60)
ms:contentKeyID: 62211149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.CheckUserAccess
dev_langs:
- CSharp
- C++
- VB
---

# CheckUserAccess Property

Gets or sets a value indicating whether access check should be performed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CHECKUSERACCESS")> _
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property CheckUserAccess As Boolean
    Get
    Set
'Usage
Dim instance As OperationPermission
Dim value As Boolean

value = instance.CheckUserAccess

instance.CheckUserAccess = value
```

``` csharp
[ColumnAttribute("CHECKUSERACCESS")]
[DataMemberAttribute]
[RequiredAttribute]
public bool CheckUserAccess { get; set; }
```

``` c++
[ColumnAttribute(L"CHECKUSERACCESS")]
[DataMemberAttribute]
[RequiredAttribute]
public:
property bool CheckUserAccess {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Gets or sets a value indicating whether access should be performed.  

## See Also

#### Reference

[OperationPermission Class](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

