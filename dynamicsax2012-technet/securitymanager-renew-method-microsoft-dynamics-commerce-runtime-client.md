---
title: SecurityManager.Renew Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Renew Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.Renew
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.securitymanager.renew(v=AX.60)
ms:contentKeyID: 62210007
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.Renew
dev_langs:
- CSharp
- C++
- VB
---

# Renew Method

User authentication renewal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function Renew As LogonCredentials
'Usage
Dim instance As SecurityManager
Dim returnValue As LogonCredentials

returnValue = instance.Renew()
```

``` csharp
public LogonCredentials Renew()
```

``` c++
public:
LogonCredentials^ Renew()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md)  
User authentication response.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

