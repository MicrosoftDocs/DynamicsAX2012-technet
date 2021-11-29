---
title: STSFormBasedAuthWebConfigUpdatingJob Constructor (String, , , ) (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: STSFormBasedAuthWebConfigUpdatingJob Constructor (String, , , )
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigUpdatingJob.#ctor(System.String,Microsoft.SharePoint.Administration.SPService,Microsoft.SharePoint.Administration.SPServer,Microsoft.SharePoint.Administration.SPJobLockType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.stsformbasedauthwebconfigupdatingjob.stsformbasedauthwebconfigupdatingjob(v=AX.60)
ms:contentKeyID: 62204476
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# STSFormBasedAuthWebConfigUpdatingJob Constructor (String, , , )


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the STSFormBasedAuthWebConfigUpdatingJob class and provides parameters for specifying key objects.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
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

Dim instance As New STSFormBasedAuthWebConfigUpdatingJob(jobName, _
    service, server, lockType)
```

``` csharp
protected STSFormBasedAuthWebConfigUpdatingJob(
    string jobName,
    SPService service,
    SPServer server,
    SPJobLockType lockType
)
```

``` c++
protected:
STSFormBasedAuthWebConfigUpdatingJob(
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

[STSFormBasedAuthWebConfigUpdatingJob Class](stsformbasedauthwebconfigupdatingjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[STSFormBasedAuthWebConfigUpdatingJob Overload](stsformbasedauthwebconfigupdatingjob-constructor-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

