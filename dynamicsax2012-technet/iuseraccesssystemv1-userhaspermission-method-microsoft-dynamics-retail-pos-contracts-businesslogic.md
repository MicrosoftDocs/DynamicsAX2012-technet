---
title: IUserAccessSystemV1.UserHasPermission Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: UserHasPermission Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUserAccessSystemV1.UserHasPermission(System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iuseraccesssystemv1.userhaspermission(v=AX.60)
ms:contentKeyID: 47128261
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUserAccessSystemV1.UserHasPermission
dev_langs:
- CSharp
- C++
- VB
---

# UserHasPermission Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Check if user has a given permission.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function UserHasPermission ( _
    userId As String, _
    permissionId As Integer _
) As Boolean
'Usage
Dim instance As IUserAccessSystemV1
Dim userId As String
Dim permissionId As Integer
Dim returnValue As Boolean

returnValue = instance.UserHasPermission(userId, _
    permissionId)
```

``` csharp
bool UserHasPermission(
    string userId,
    int permissionId
)
```

``` c++
bool UserHasPermission(
    String^ userId, 
    int permissionId
)
```

#### Parameters

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - permissionId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if user has permission, false otherwise.  

## See Also

#### Reference

[IUserAccessSystemV1 Interface](iuseraccesssystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

