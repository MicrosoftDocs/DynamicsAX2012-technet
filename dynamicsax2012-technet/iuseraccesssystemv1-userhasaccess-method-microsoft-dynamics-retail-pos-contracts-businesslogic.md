---
title: IUserAccessSystemV1.UserHasAccess Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: UserHasAccess Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUserAccessSystemV1.UserHasAccess(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iuseraccesssystemv1.userhasaccess(v=AX.60)
ms:contentKeyID: 47128840
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUserAccessSystemV1.UserHasAccess
dev_langs:
- CSharp
- C++
- VB
---

# UserHasAccess Method

Checks if the user has access to execute the given operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function UserHasAccess ( _
    userID As String, _
    operationID As PosisOperations _
) As Boolean
'Usage
Dim instance As IUserAccessSystemV1
Dim userID As String
Dim operationID As PosisOperations
Dim returnValue As Boolean

returnValue = instance.UserHasAccess(userID, _
    operationID)
```

``` csharp
bool UserHasAccess(
    string userID,
    PosisOperations operationID
)
```

``` c++
bool UserHasAccess(
    String^ userID, 
    PosisOperations operationID
)
```

#### Parameters

  - userID  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - operationID  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Trueif the user has access to that operation orfalseotherwise.  

## See Also

#### Reference

[IUserAccessSystemV1 Interface](iuseraccesssystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

