---
title: IBusinessLogicV1.UserAccessSystem Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: UserAccessSystem Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogicV1.UserAccessSystem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.ibusinesslogicv1.useraccesssystem(v=AX.60)
ms:contentKeyID: 47128211
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogicV1.UserAccessSystem
dev_langs:
- CSharp
- C++
- VB
---

# UserAccessSystem Property

Gets the user access system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property UserAccessSystem As IUserAccessSystem
    Get
'Usage
Dim instance As IBusinessLogicV1
Dim value As IUserAccessSystem

value = instance.UserAccessSystem
```

``` csharp
IUserAccessSystem UserAccessSystem { get; }
```

``` c++
property IUserAccessSystem^ UserAccessSystem {
    IUserAccessSystem^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUserAccessSystem](iuseraccesssystem-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)  
Returns [IUserAccessSystem](iuseraccesssystem-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md).  

## See Also

#### Reference

[IBusinessLogicV1 Interface](ibusinesslogicv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

