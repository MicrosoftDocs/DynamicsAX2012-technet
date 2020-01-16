---
title: CommerceRuntimeConfigDeploymentJob.IsForActivation Property  (Microsoft.Dynamics.Retail.SP.CommerceRuntime)
TOCTitle: IsForActivation Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJob.IsForActivation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commerceruntime.commerceruntimeconfigdeploymentjob.isforactivation(v=AX.60)
ms:contentKeyID: 62204025
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJob.IsForActivation
dev_langs:
- CSharp
- C++
- VB
---

# IsForActivation Property

Gets the value indicating whether this job is for activation or deactivation.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommerceRuntime](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Protected Overrides ReadOnly Property IsForActivation As Boolean
    Get
'Usage
Dim value As Boolean

value = Me.IsForActivation
```

``` csharp
protected override bool IsForActivation { get; }
```

``` c++
protected:
virtual property bool IsForActivation {
    bool get () override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CommerceRuntimeConfigDeploymentJob Class](commerceruntimeconfigdeploymentjob-class-microsoft-dynamics-retail-sp-commerceruntime.md)

[Microsoft.Dynamics.Retail.SP.CommerceRuntime Namespace](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)

