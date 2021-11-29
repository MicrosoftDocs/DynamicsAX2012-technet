---
title: SecurityManager.GetOperationPermissionsById Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOperationPermissionsById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetOperationPermissionsById(Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.getoperationpermissionsbyid(v=AX.60)
ms:contentKeyID: 62202885
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetOperationPermissionsById
dev_langs:
- CSharp
- C++
- VB
---

# GetOperationPermissionsById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets operation permission settings for server function to execute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOperationPermissionsById ( _
    operationId As RetailOperation _
) As OperationPermission
'Usage
Dim instance As SecurityManager
Dim operationId As RetailOperation
Dim returnValue As OperationPermission

returnValue = instance.GetOperationPermissionsById(operationId)
```

``` csharp
public OperationPermission GetOperationPermissionsById(
    RetailOperation operationId
)
```

``` c++
public:
OperationPermission^ GetOperationPermissionsById(
    RetailOperation operationId
)
```

#### Parameters

  - operationId  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
OperationPermission object.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

