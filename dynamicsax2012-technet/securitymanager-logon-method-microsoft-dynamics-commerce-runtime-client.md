---
title: SecurityManager.LogOn Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: LogOn Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.LogOn(Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.logon(v=AX.60)
ms:contentKeyID: 62211449
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.LogOn
dev_langs:
- CSharp
- C++
- VB
---

# LogOn Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

User authentication.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function LogOn ( _
    connectionRequest As ConnectionRequest _
) As LogonCredentials
'Usage
Dim instance As SecurityManager
Dim connectionRequest As ConnectionRequest
Dim returnValue As LogonCredentials

returnValue = instance.LogOn(connectionRequest)
```

``` csharp
public LogonCredentials LogOn(
    ConnectionRequest connectionRequest
)
```

``` c++
public:
LogonCredentials^ LogOn(
    ConnectionRequest^ connectionRequest
)
```

#### Parameters

  - connectionRequest  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest](connectionrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md)  
User authentication response.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

