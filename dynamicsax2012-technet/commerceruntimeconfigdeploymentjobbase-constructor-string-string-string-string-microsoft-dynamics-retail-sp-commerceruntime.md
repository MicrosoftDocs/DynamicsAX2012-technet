---
title: CommerceRuntimeConfigDeploymentJobBase Constructor (String, , String, String, String) (Microsoft.Dynamics.Retail.SP.CommerceRuntime)
TOCTitle: CommerceRuntimeConfigDeploymentJobBase Constructor (String, , String, String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJobBase.#ctor(System.String,Microsoft.SharePoint.Administration.SPWebApplication,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commerceruntime.commerceruntimeconfigdeploymentjobbase.commerceruntimeconfigdeploymentjobbase(v=AX.60)
ms:contentKeyID: 62204685
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommerceRuntimeConfigDeploymentJobBase Constructor (String, , String, String, String)

Initializes a new instance of the CommerceRuntimeConfigDeploymentJobBase class and provides parameters for specifying key objects.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommerceRuntime](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    jobName As String, _
    webApplication As SPWebApplication, _
    commerceRuntimeSourceFileRelativePath As String, _
    workflowFoundationSourceFileRelativePath As String, _
    rtsBindingsSourceFileRelativePath As String _
)
'Usage
Dim jobName As String
Dim webApplication As SPWebApplication
Dim commerceRuntimeSourceFileRelativePath As String
Dim workflowFoundationSourceFileRelativePath As String
Dim rtsBindingsSourceFileRelativePath As String

Dim instance As New CommerceRuntimeConfigDeploymentJobBase(jobName, _
    webApplication, commerceRuntimeSourceFileRelativePath, _
    workflowFoundationSourceFileRelativePath, _
    rtsBindingsSourceFileRelativePath)
```

``` csharp
protected CommerceRuntimeConfigDeploymentJobBase(
    string jobName,
    SPWebApplication webApplication,
    string commerceRuntimeSourceFileRelativePath,
    string workflowFoundationSourceFileRelativePath,
    string rtsBindingsSourceFileRelativePath
)
```

``` c++
protected:
CommerceRuntimeConfigDeploymentJobBase(
    String^ jobName, 
    SPWebApplication^ webApplication, 
    String^ commerceRuntimeSourceFileRelativePath, 
    String^ workflowFoundationSourceFileRelativePath, 
    String^ rtsBindingsSourceFileRelativePath
)
```

#### Parameters

  - jobName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - webApplication  
    Type: SPWebApplication  

<!-- end list -->

  - commerceRuntimeSourceFileRelativePath  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - workflowFoundationSourceFileRelativePath  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rtsBindingsSourceFileRelativePath  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CommerceRuntimeConfigDeploymentJobBase Class](commerceruntimeconfigdeploymentjobbase-class-microsoft-dynamics-retail-sp-commerceruntime.md)

[CommerceRuntimeConfigDeploymentJobBase Overload](commerceruntimeconfigdeploymentjobbase-constructor-microsoft-dynamics-retail-sp-commerceruntime.md)

[Microsoft.Dynamics.Retail.SP.CommerceRuntime Namespace](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)

