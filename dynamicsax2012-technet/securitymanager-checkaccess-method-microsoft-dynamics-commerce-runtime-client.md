---
title: SecurityManager.CheckAccess Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CheckAccess Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.CheckAccess(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal,System.String[],Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation,System.Boolean,System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.checkaccess(v=AX.60)
ms:contentKeyID: 62212958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.CheckAccess
dev_langs:
- CSharp
- C++
- VB
---

# CheckAccess Method

Performs Check Access for the user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub CheckAccess ( _
    commercePrincipal As CommercePrincipal, _
    allowedRoles As String(), _
    operationId As RetailOperation, _
    deviceTokenRequired As Boolean, _
    actionContext As Object _
)
'Usage
Dim instance As SecurityManager
Dim commercePrincipal As CommercePrincipal
Dim allowedRoles As String()
Dim operationId As RetailOperation
Dim deviceTokenRequired As Boolean
Dim actionContext As Object

instance.CheckAccess(commercePrincipal, _
    allowedRoles, operationId, deviceTokenRequired, _
    actionContext)
```

``` csharp
public void CheckAccess(
    CommercePrincipal commercePrincipal,
    string[] allowedRoles,
    RetailOperation operationId,
    bool deviceTokenRequired,
    Object actionContext
)
```

``` c++
public:
void CheckAccess(
    CommercePrincipal^ commercePrincipal, 
    array<String^>^ allowedRoles, 
    RetailOperation operationId, 
    bool deviceTokenRequired, 
    Object^ actionContext
)
```

#### Parameters

  - commercePrincipal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - allowedRoles  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

<!-- end list -->

  - operationId  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - deviceTokenRequired  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - actionContext  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

