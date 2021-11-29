---
title: CommerceRuntimeConfigDeploymentJobBase Class (Microsoft.Dynamics.Retail.SP.CommerceRuntime)
TOCTitle: CommerceRuntimeConfigDeploymentJobBase Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJobBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commerceruntime.commerceruntimeconfigdeploymentjobbase(v=AX.60)
ms:contentKeyID: 62204050
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJobBase
dev_langs:
- CSharp
- C++
- VB
---

# CommerceRuntimeConfigDeploymentJobBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Job that installs or uninstalls the commonRuntime.config and workflowFoundation.config files next to the web.config file in a specified web app.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommerceRuntime](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class CommerceRuntimeConfigDeploymentJobBase _
    Inherits SPJobDefinition
'Usage
Dim instance As CommerceRuntimeConfigDeploymentJobBase
```

``` csharp
public abstract class CommerceRuntimeConfigDeploymentJobBase : SPJobDefinition
```

``` c++
public ref class CommerceRuntimeConfigDeploymentJobBase abstract : public SPJobDefinition
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPAutoSerializingObject  
    SPPersistedObject  
      SPJobDefinition  
        Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJobBase  
          [Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJob](commerceruntimeconfigdeploymentjob-class-microsoft-dynamics-retail-sp-commerceruntime.md)  
          [Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigRemovalJob](commerceruntimeconfigremovaljob-class-microsoft-dynamics-retail-sp-commerceruntime.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommerceRuntime Namespace](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)

