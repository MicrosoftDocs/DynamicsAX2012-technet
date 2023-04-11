---
title: CommerceRuntimeConfigDeploymentJobBase Constructor (String, , , ) (Microsoft.Dynamics.Retail.SP.CommerceRuntime)
TOCTitle: CommerceRuntimeConfigDeploymentJobBase Constructor (String, , , )
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJobBase.#ctor(System.String,Microsoft.SharePoint.Administration.SPService,Microsoft.SharePoint.Administration.SPServer,Microsoft.SharePoint.Administration.SPJobLockType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commerceruntime.commerceruntimeconfigdeploymentjobbase.commerceruntimeconfigdeploymentjobbase(v=AX.60)
ms:contentKeyID: 62205345
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommerceRuntimeConfigDeploymentJobBase Constructor (String, , , )


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the CommerceRuntimeConfigDeploymentJobBase class and provides parameters for specifying key objects.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommerceRuntime](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    jobName As String, _
    service As SPService, _
    server As SPServer, _
    lockType As SPJobLockType _
)
'Usage
Dim jobName As String
Dim service As SPService
Dim server As SPServer
Dim lockType As SPJobLockType

Dim instance As New CommerceRuntimeConfigDeploymentJobBase(jobName, _
    service, server, lockType)
```

``` csharp
protected CommerceRuntimeConfigDeploymentJobBase(
    string jobName,
    SPService service,
    SPServer server,
    SPJobLockType lockType
)
```

``` c++
protected:
CommerceRuntimeConfigDeploymentJobBase(
    String^ jobName, 
    SPService^ service, 
    SPServer^ server, 
    SPJobLockType lockType
)
```

#### Parameters

  - jobName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - service  
    Type: SPService  

<!-- end list -->

  - server  
    Type: SPServer  

<!-- end list -->

  - lockType  
    Type: SPJobLockType  

## See Also

#### Reference

[CommerceRuntimeConfigDeploymentJobBase Class](commerceruntimeconfigdeploymentjobbase-class-microsoft-dynamics-retail-sp-commerceruntime.md)

[CommerceRuntimeConfigDeploymentJobBase Overload](commerceruntimeconfigdeploymentjobbase-constructor-microsoft-dynamics-retail-sp-commerceruntime.md)

[Microsoft.Dynamics.Retail.SP.CommerceRuntime Namespace](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)

