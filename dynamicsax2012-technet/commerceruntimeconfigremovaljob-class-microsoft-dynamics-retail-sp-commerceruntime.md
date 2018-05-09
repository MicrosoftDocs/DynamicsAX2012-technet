---
title: CommerceRuntimeConfigRemovalJob Class (Microsoft.Dynamics.Retail.SP.CommerceRuntime)
TOCTitle: CommerceRuntimeConfigRemovalJob Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigRemovalJob
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commerceruntime.commerceruntimeconfigremovaljob(v=AX.60)
ms:contentKeyID: 62205085
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigRemovalJob
dev_langs:
- CSharp
- C++
- VB
---

# CommerceRuntimeConfigRemovalJob Class

Job that removes the commonruntime.config file next to the web.config file the web app.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommerceRuntime](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Class CommerceRuntimeConfigRemovalJob _
    Inherits CommerceRuntimeConfigDeploymentJobBase
'Usage
Dim instance As CommerceRuntimeConfigRemovalJob
```

``` csharp
public class CommerceRuntimeConfigRemovalJob : CommerceRuntimeConfigDeploymentJobBase
```

``` c++
public ref class CommerceRuntimeConfigRemovalJob : public CommerceRuntimeConfigDeploymentJobBase
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  SPAutoSerializingObject  
    SPPersistedObject  
      SPJobDefinition  
        [Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigDeploymentJobBase](commerceruntimeconfigdeploymentjobbase-class-microsoft-dynamics-retail-sp-commerceruntime.md)  
          Microsoft.Dynamics.Retail.SP.CommerceRuntime.CommerceRuntimeConfigRemovalJob  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommerceRuntime Namespace](microsoft-dynamics-retail-sp-commerceruntime-namespace.md)

