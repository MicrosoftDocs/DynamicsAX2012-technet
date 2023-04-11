---
title: SecurityManager.GetOperationPermission Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOperationPermission Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetOperationPermission(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.getoperationpermission(v=AX.60)
ms:contentKeyID: 65322599
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetOperationPermission
dev_langs:
- CSharp
- C++
- VB
---

# GetOperationPermission Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOperationPermission ( _
    settings As QueryResultSettings _
) As PagedResult(Of OperationPermission)
'Usage
Dim instance As SecurityManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of OperationPermission)

returnValue = instance.GetOperationPermission(settings)
```

``` csharp
public PagedResult<OperationPermission> GetOperationPermission(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<OperationPermission^>^ GetOperationPermission(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[OperationPermission](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

