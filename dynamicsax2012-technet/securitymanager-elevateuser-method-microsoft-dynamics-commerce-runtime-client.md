---
title: SecurityManager.ElevateUser Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ElevateUser Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ElevateUser(Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.elevateuser(v=AX.60)
ms:contentKeyID: 62209447
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ElevateUser
dev_langs:
- CSharp
- C++
- VB
---

# ElevateUser Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

User elevation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function ElevateUser ( _
    connectionRequest As ConnectionRequest, _
    retailOperation As RetailOperation _
) As LogonCredentials
'Usage
Dim instance As SecurityManager
Dim connectionRequest As ConnectionRequest
Dim retailOperation As RetailOperation
Dim returnValue As LogonCredentials

returnValue = instance.ElevateUser(connectionRequest, _
    retailOperation)
```

``` csharp
public LogonCredentials ElevateUser(
    ConnectionRequest connectionRequest,
    RetailOperation retailOperation
)
```

``` c++
public:
LogonCredentials^ ElevateUser(
    ConnectionRequest^ connectionRequest, 
    RetailOperation retailOperation
)
```

#### Parameters

  - connectionRequest  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest](connectionrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - retailOperation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md)  
User authentication response.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

