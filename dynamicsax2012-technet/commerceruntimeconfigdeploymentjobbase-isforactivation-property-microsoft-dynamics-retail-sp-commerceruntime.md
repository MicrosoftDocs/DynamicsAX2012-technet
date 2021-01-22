---
title: CommerceRuntimeConfigDeploymentJobBase.IsForActivation Property  (Microsoft.Dynamics.Retail.SP.CommerceRuntime)
TOCTitle: IsForActivation Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJobBase.IsForActivation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commerceruntime.commerceruntimeconfigdeploymentjobbase.isforactivation(v=AX.60)
ms:contentKeyID: 62206945
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJobBase.IsForActivation
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
Protected MustOverride ReadOnly Property IsForActivation As Boolean
    Get
'Usage
Dim value As Boolean

value = Me.IsForActivation
```

``` csharp
protected abstract bool IsForActivation { get; }
```

``` c++
protected:
virtual property bool IsForActivation {
    bool get () abstract;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CommerceRuntimeConfigDeploymentJobBase Class](commerceruntimeconfigdeploymentjobbase-class-microsoft-dynamics-retail-sp-commerceruntime.md)

[Microsoft.Dynamics.Retail.SP.CommerceRuntime Namespace](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)

